# OpenMRS Mobile Automation - Maestro

This project contains automated tests for the OpenMRS Mobile application using the [Maestro](https://maestro.mobile.dev/) framework.

## Prerequisites

- [Maestro CLI](https://maestro.mobile.dev/getting-started/installing-maestro) installed.
- Android Emulator or physical device connected.
- OpenMRS Mobile APK installed on the device.

## How to run the tests

To run the main login and provider management flow:

```bash
maestro test openmrs_login_manage_providers.yml
```

## Project Structure - Test 

- `openmrs_login_manage_providers.yml`: Main test flow (Login -> Dashboard -> Manage Providers).
- `screenshots/`: (Automatically generated) Contains test evidences.

##  Test Cases

### Login and Manage Providers
1. Open the application.
2. Validate the login screen.
3. Enter credentials (admin/Admin123).
4. Select the session location (Mobile Clinic).
5. Perform login.
6. Validate dashboard access.
7. Access the "Manage Providers" screen.
8. Validate the presence of providers in the list.
