# Java - List Conferences How-To Guide

This project serves as a guide to help you build an application with FreeClimb. View this how-to guide on [FreeClimb.com](https://docs.freeclimb.com/docs/list-conferences#section-java). Specifically, the project will:

- List information about current and past conferences

## Setting up your new app within your FreeClimb account

To get started using a FreeClimb account, follow the instructions [here](https://docs.freeclimb.com/docs/getting-started-with-freeclimb).

## Setting up the how-to guide

1. Configure environment variables.

   | ENV VARIABLE | DESCRIPTION                                                                                                                              |
   | ------------ | ---------------------------------------------------------------------------------------------------------------------------------------- |
   | ACCOUNT_ID   | Account ID which can be found under [API credentials](https://www.freeclimb.com/dashboard/portal/account/authentication) in Dashboard           |
   | API_KEY   | API key which can be found under [API credentials](https://www.freeclimb.com/dashboard/portal/account/authentication) in Dashboard |

## Building and runnning the how-to guide

1. Build and run the application using command:

   ```bash
   $ gradle build && java -Dserver.port=3000 -jar build/libs/gs-spring-boot-0.1.0.jar
   ```

## Getting Help

If you are experiencing difficulties, [contact support](https://freeclimb.com/support).
