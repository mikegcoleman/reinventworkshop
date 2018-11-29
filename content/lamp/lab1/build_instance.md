+++
title = "1.1 - Build the LAMP instance"
weight = 10
+++

The first step in deploying the sample application is creating a LAMP stack instance in Lightsail. 

{{% notice tip %}}
Be sure to create all the resources for this workshop in the eu-west-1 (Ireland) region
{{% /notice %}}

* From the <a href="https://lightsail.aws.amazon.com/ls/webapp/home/" target="_blank">Lightsail console home page</a> click ***Create Instance***

    ![](../../images/1-1-1.jpg?classes=border)

* Choose the region for your instance. Under ***Instance Location*** click ***Change AWS Region and Availability Zone*** and select the ***eu-west-1 (Ireland)*** region. 

    ![](../../images/region.jpg?classes=border)

* Make sure that ***Linux/Unix*** is selected under ***Select a platform***, and then under ***Blueprint*** choose ***LAMP (PHP5)***
    
    ![](../../images/lamp-blueprint.jpg?classes=border)


* Name the instance ***PHP-fe-1***

    ![](../../images/lamp-name.jpg?classes=border)

* Click ***Create instance***

    ![](../../images/lamp-create.jpg?classes=border)

