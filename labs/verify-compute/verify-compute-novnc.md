# Verify Compute Instance Setup

## Introduction
This lab will show you how to login to your pre-created compute instance running on Oracle Cloud.

*Estimated Time*: 5 minutes

### Objectives
In this lab, you will:
- Learn how to connect to your compute instance using Remote Desktop

### Prerequisites

This lab assumes you have:
- Successfully submitted a reservation using the **Run on LiveLabs** option
- Your reservation has been Successfully executed and valid remote desktop URL provided in the output

## Task 1: Access the Graphical Remote Desktop
For ease of execution of this workshop, your VM instance has been pre-configured with a remote graphical desktop accessible using any modern browser on your laptop or workstation. Proceed as detailed below to login.

1. Now that your instance has been provisioned, if not already on **My Reservations** page, then:
    - Click on the drop-down arrow next to your *Username*
    - Click on *My Reservations*

   ![my reservation](images/my-reservations.png "my reservation")

2. Find the request you submitted from the list displayed (only one item will be displayed if this is your first request), then click on **Launch Workshop**

    ![my reservation completed](images/my-reservation-completed.png "my reservation completed")

    >**Note:** The *Launch Workshop* link will be visible only when provisioning is completed

3. Click on **Login info** and then on **Launch Remote Desktop** link.

    ![Login information](images/login-info.png "Login Information")

    This should take you directly to your remote desktop in a single click.

    ![noVNC launch remote desktop](images/novnc-launch-get-started-2.png "noVNC launch remote desktop ")

    >**Note:**  While rare, you may see an error titled **Deceptive Site Ahead** or similar depending on your browser type as shown below.

    Public IP addresses used for LiveLabs provisioning comes from a pool of reusable addresses and this error is due to the fact that the address was previously used by a compute instance long terminated, but that wasn't properly secured, got compromised and was flagged.

    You can safely ignore and proceed by clicking on **Details**, and finally on **Visit this unsafe site**.

    ![site error message](images/novnc-deceptive-site-error.png "site error message ")

4. During the lifetime of your environment, you may return to this page to request an extension. To further extend the duration of your reservation, click on **Extend Workshop Reservation**

    ![Extend Workshop Reservation](images/extend-my-reservation.png "Extend Workshop Reservation")

    >**Note:**  You may extend your reservation up to 4 times yielding a maximum lifetime equal to double of the initial duration.


You may now proceed to the next lab.


## Acknowledgements
* **Author** - Rene Fontcha, LiveLabs Platform Lead, NA Technology
* **Contributors** - LiveLabs Team
* **Last Updated By/Date** - Rene Fontcha, LiveLabs Platform Lead, NA Technology, August 2021
