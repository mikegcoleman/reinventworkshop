+++
title = "1.3 - Create the load balancer"
weight = 30
+++

In order to provide scalability and fault tolerance you will be deploying your web front end behind a Lightsail load balancer. Lightsail load balancers handle both HTTP and HTTPS traffic on ports 80 and 443 respectively. For HTTPS you can request a free certificate from AWS certificate manager (although configuring HTTPS connections is out of scope for this workshop).

* Return to the <a href="https://lightsail.aws.amazon.com/ls/webapp/home/" target="_blank">Lightsail console home page</a> and choose ***Networking*** from the horizontal menu. 

    ![](../../images/2-4-1.jpg?classes=border)

* Click ***Create Load Balancer***

    ![](../../images/2-4-2.jpg?classes=border)

{{% notice tip %}}
Make sure you're deploying your database into the eu-west-1 (Ireland) region.
{{% /notice %}}

* Choose the region for your instance. Under ***Instance Location*** click ***Change AWS Region and Availability Zone*** and select the ***eu-west-1 (Ireland)*** region.

    ![](../../images/region.jpg?classes=border)

* Scroll down and enter ***todo-lb*** for the load balancer name

    ![](../../images/2-4-3.jpg?classes=border)

* Click ***Create Load Balancer***

    ![](../../images/2-4-4.jpg?classes=border)