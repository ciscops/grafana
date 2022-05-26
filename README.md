# Setting Up a Grafana Dashboard - Guide

## Getting Started

These instructions will take you through the setting up a Grafana dashboard connected to a MongoDB data source.

__In this lab you will__
1. Set Up Grafana
2. Connect to MongoDB Data Source
3. Create a basic Dashboard

__You will need:__
* Grafana
* A MongoDB Database

## Grafana Set Up

###Installing Grafana

Since we're setting up a Grafana dashboard in this lab, we'll need to [install](https://grafana.com/docs/grafana/latest/installation/) Grafana. Please select your corresponding operating system and follow the instructions.

Next, you'll want to [configure](https://grafana.com/docs/grafana/latest/administration/configuration/) Grafana. Again, follow the instructions for your operating system. As noted in the configuration guide, you'll need to remove comments in the .ini files by removing the ''';''' at the beginning of the lines you want to change.

### Logging In

1. Open your web browser and go to http://localhost:3000/. The default HTTP port that Grafana listens to is '''3000''' unless you configured a different port in the previous step. If you are not hosting Grafana locally, then go to http://[host]:3000/ instead.
2. On the login page, enter '''admin''' as the username and password.
3. Click **Log in**. If the login is successful, you will see a prompt to change the password.
4. Click **OK** on the prompt, then change your password.

### Creating a Dashboard

1. Click the **+** icon on the side menu.
2. On the dashboard, click **Add an empty panel**.

![alt text](images/make-grafana-dashboard.gif "Make Grafana Dashboard")