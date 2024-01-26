# GoogleCloudRDP

This shell script automates the setup of a remote desktop environment on a Debian system using Chrome Remote Desktop and XFCE for Google Cloud CLI.

## Prerequisites

- A Debian system
- Internet connection

## Usage

1. Clone the repository or download the `rdp.sh` script:

    ```bash
    git clone https://github.com/whitehackeruz/GoogleCloudRDP.git
    ```

2. Navigate to the script directory:

    ```bash
    cd GoogleCloudRDP
    ```

3. Make the script executable:

    ```bash
    chmod +x rdp.sh
    ```

4. Run the script:

    ```bash
    ./rdp.sh
    ```

5. After running the script, visit [https://remotedesktop.google.com/headless](https://remotedesktop.google.com/headless) to obtain the SSH setup script.

6. Copy the SSH setup script and paste it into your terminal.

7. Follow the on-screen instructions, including providing pin codes when prompted.

8. Once set up, you can connect to your remote desktop by visiting [https://remotedesktop.google.com/access](https://remotedesktop.google.com/access).

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
