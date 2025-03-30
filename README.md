# Installing Java on Windows

## Step 1: Download Java JDK
1. Open a web browser and go to the [Oracle JDK Download Page](https://www.oracle.com/java/technologies/javase-downloads.html).
2. Select the latest Java SE Development Kit (JDK) for Windows.
3. Choose the **Windows x64 Installer** (`.exe` file) and download it.

## Step 2: Install Java JDK
1. Locate the downloaded `.exe` file and double-click to run it.
2. Follow the installation wizard:
   - Click **Next** to proceed.
   - Choose an installation location (or leave it as default) and click **Next**.
   - Click **Install** to start the installation.
3. Once the installation is complete, click **Close**.

## Step 3: Set Up Environment Variables
1. Open the **Start Menu** and search for `Environment Variables`.
2. Click on **Edit the system environment variables**.
3. In the **System Properties** window, click on **Environment Variables**.
4. Under **System variables**, find **Path** and click **Edit**.
5. Click **New** and add the path to the `bin` folder of your Java installation, e.g.,
   ```sh
   C:\Program Files\Java\jdk-XX.X.X\bin
