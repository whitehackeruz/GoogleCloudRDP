# 
# GoogleCloudRDP
This shell script automates the setup of a remote desktop environment on a Linux system using Chrome Remote Desktop and XFCE for Google Cloud CLI.

## Prerequisites

- A Linux system (Ubuntu, Debian, etc.)
- Internet connection

## Usage

1. Clone the repository or download the `rdp.sh` script:

    ```bash
    git clone https://github.com/your-username/rdp-script.git
    ```

2. Navigate to the script directory:

    ```bash
    cd rdp-script
    ```

3. Make the script executable:

    ```bash
    chmod +x rdp.sh
    ```

4. Run the script:

    ```bash
    ./rdp.sh
    ```

Follow the on-screen instructions to complete the setup.

## What it does

The script performs the following actions:

- Downloads and installs Chrome Remote Desktop and Google Chrome.
- Installs necessary packages for the XFCE desktop environment.
- Configures Chrome Remote Desktop to use the XFCE session.
- Disables the lightdm service.

## Notes

- Review and understand the script before running it.
- The script assumes it is run with the necessary privileges.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
