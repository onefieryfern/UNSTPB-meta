# Eduroam connection guide - UNSTPB

## Within UNSTPB

### Quick jump

Mobile devices

- [Android](#on-android)
- [iOS/iPadOS](#on-iosipados)

Laptops

- [Windows](#on-windows)
- [macOS](#on-macos)
- [Linux](#on-linux)

### On Android

> [!NOTE]
> The images in this section are for Samsung devices. Your device's interface
> may vary. (See the [`images`](images/) folder for screenshots for
> other manufacturers)

> [!WARNING]
> If you have previously tried to connect to the `eduroam` network, first
> forget the `eduroam` network and then follow this guide.

1. Pick the `eduroam` network in your Wi-Fi settings

<p align="center">
    <img src="images/eduroam-android-samsung-00.jpg" width="400"
        alt="A list of available Wi-Fi networks, including eduroam" />
</p>

2. Enter your _my.upb_ username (i.e. the part before the `@` of your
   student email address) into the `Identity` field
3. Enter your _my.upb_ password into the `Password` field

<p align="center">
    <img src="images/eduroam-android-samsung-01.jpg" width="400"
        alt="Settings page for the eduroam network, the first two items are
        fields titled Identity and Password, then a drop-down titled CA Certificate,
        then a toggle called Auto reconnect, a button titled View more
        and a button titled Connect" />
</p>

4. Under `CA Certificate`, choose `Trust on first use (TOFU)`

> [!TIP]
> If `Trust on first use` is not available, choose `Don't validate`

<p align="center">
    <img src="images/eduroam-android-samsung-02.jpg" width="400"
        alt="The same settings page, with the CA Connect drop-down opened, listing
        the following options: Select certificate, Use system certificates,
        Trust on first use (TOFU), Don't validate" />
</p>

5. Press `Connect`. You will be asked to trust the CA certificate provided
   by the network. Inspect the certificate and press `Trust`

<p align="center">
    <img src="images/eduroam-android-samsung-03.jpg" width="400"
        alt="The same settings page, with the Connect button now pressable" />
    </p>
<p align="center">
    <img src="images/eduroam-android-samsung-04.jpg" width="400"
        alt="A pop-up titled Security Certificate, where the user is asked
        to inspect the CA certificate provided by the network,
        with two buttons at the bottom titled Cancel and Trust" />
</p>

6. You should now be connected to the `eduroam` network

### On iOS/iPadOS

1. Pick the `eduroam` network in your Wi-Fi settings

<p align="center">
    <img src="images/eduroam-iOS-00.jpeg" width="400"
        alt="A list of available Wi-Fi networks, including eduroam" />
</p>

2. Enter your _my.upb_ username (i.e. the part before the `@` of your
   student email address) into the `Username` field
3. Enter your _my.upb_ password into the `Password` field

<p align="center">
    <img src="images/eduroam-iOS-01.jpeg" width="400"
        alt="A pop-up titled Join eduroam, with two fields titled
        Username and Password" />
</p>

4. Press the tick symbol in the top right corner to connect. You will be asked
   to trust a certificate provided by the network. Inspect the certificate
   and press `Trust`

<p align="center">
    <img src="images/eduroam-iOS-02.jpeg" width="400"
        alt="The same pop-up, with the tick button now pressable" />
</p>
<p align="center">
    <img src="images/eduroam-iOS-03.jpeg" width="400"
        alt="A pop-up titled Certificate, where the user is asked to inspect
        the certificate provided by the network, with two buttons at the top,
        a button with a cross on the left and a button titled Trust
        on the right" />
</p>

5. You should now be connected to the `eduroam` network

### On Windows

> [!NOTE]
> This section is written for Windows 11, but it should be similar for older
> Windows versions

1. Pick the `eduroam` network in your Wi-Fi settings and click `Connect`

<p align="center">
    <img src="images/eduroam-Windows-00.png" width="400"
        alt="A list of available Wi-Fi networks, including eduroam" />
</p>
<p align="center">
    <img src="images/eduroam-Windows-01.png" width="400"
        alt="The same list, with eduroam selected, with a ticked checkbox
        titled Connect automatically and a Connect button" />
</p>

2. Enter your _my.upb_ username (i.e. the part before the `@` of your
   student email address) into the `Username` field
3. Enter your _my.upb_ password into the `Password` field

<p align="center">
    <img src="images/eduroam-Windows-02.png" width="400"
        alt="The same list, with eduroam selected, now with the text Enter your
        username and password, and two fields titled Username and Password" />
</p>

4. Click `OK`. You will be asked to trust a certificate provided by the network
   (`Continue connecting?`). Inspect the certificate and press `Connect`

<p align="center">
    <img src="images/eduroam-Windows-03.png" width="400"
        alt="The same list, with eduroam selected, now with the credentials
        inputted" />
</p>
<p align="center">
    <img src="images/eduroam-Windows-04.png" width="400"
        alt="The same list, with eduroam selected, now with the text
        Continue connecting? and two buttons titled Connect and Cancel" />
</p>

5. You should now be connected to the `eduroam` network

### On macOS

> [!WARNING]
> Use the Wi-Fi menu in the menu bar, _not_ the Wi-Fi page in the
> System Settings app, as it is buggy when connecting to the `eduroam` network
> and may cause confusion (as it asks for credentials multiple times)

1. Pick the `eduroam` network in your Wi-Fi settings

> [!TIP]
> You may need to press the `Other Networks` button to see
> available Wi-Fi networks

<p align="center">
    <img src="images/eduroam-macOS-00.png" width="400"
        alt="A list of available personal hotspots and known networks,
        not including eduroam" />
</p>
<p align="center">
    <img src="images/eduroam-macOS-01.png" width="400"
        alt="A list of available personal hotspots, known networks,
        and available Wi-Fi networks, including eduroam" />
</p>

2. Enter your _my.upb_ username (i.e. the part before the `@` of your
   student email address) into the `Account Name` field
3. Enter your _my.upb_ password into the `Password` field

<p align="center">
    <img src="images/eduroam-macOS-02.png" width="500"
        alt="A pop-up titled Join eduroam, with two fields titled
        Username and Password, a ticked checkbox with the text
        Remember this information, and two buttons titled Cancel and OK" />
</p>

4. Click `OK`. You will be asked to trust a certificate provided by the network.
   Inspect the certificate and press `Continue`

<p align="center">
    <img src="images/eduroam-macOS-03.png" width="500"
        alt="The same pop-up, with the login credentials inputted" />
</p>
<p align="center">
    <img src="images/eduroam-macOS-04.png" width="600"
        alt="A pop-up titled Verify Certificate, where the user is asked to inspect
        the certificate provided by the network, with three buttons:
        Show Certificate, Cancel, and Continue" />
</p>

5. You should now be connected to the `eduroam` network

### On Linux

> [!NOTE]
> This section is written for Linux distros that use `NetworkManager` and have
> `nmtui` available

1. Run `nmtui` in your terminal
2. Pick `Edit a connection` using the arrow keys and the enter key

<p align="center">
    <img src="images/eduroam-linux-nm-00.png" width="600"
        alt="" />
</p>

3. Pick `<Add>`

<p align="center">
    <img src="images/eduroam-linux-nm-01.png" width="600"
        alt="" />
</p>

4. In the `New Connection` pop-up, pick `Wi-Fi` and use the right arrow key to
   pick `<Create>`

<p align="center">
    <img src="images/eduroam-linux-nm-02.png" width="600"
        alt="" />
</p>
<p align="center">
    <img src="images/eduroam-linux-nm-03.png" width="600"
        alt="" />
</p>

5. Pick a `Profile name`, `eduroam` or `eduroam UPB` are good choices

   In the `SSID` field, enter `eduroam`, and for the `Mode` pick `Client`

   For `Security` pick `WPA & WPA2 Enterprise`. New fields should now appear

   For `Authentication` pick `PEAP`, and for `Inner authentication` pick
   `MSCHAPv2`

<p align="center">
    <img src="images/eduroam-linux-nm-04.png" width="600"
        alt="" />
</p>

6. Enter your _my.upb_ username (i.e. the part before the `@` of your
   student email address) into the `Username` field
7. Enter your _my.upb_ password into the `Password` field
8. The rest of the fields are to be left blank. Now pick `OK`

<p align="center">
    <img src="images/eduroam-linux-nm-05.png" width="600"
        alt="" />
</p>

9. Pick `<Back>` or use the escape key, and then pick `Activate a connection`

<p align="center">
    <img src="images/eduroam-linux-nm-06.png" width="600"
        alt="" />
</p>
<p align="center">
    <img src="images/eduroam-linux-nm-07.png" width="600"
        alt="" />
</p>

10. Pick `<Rescan Wi-Fi>` if `eduroam` does not show up in the Wi-Fi list

<p align="center">
    <img src="images/eduroam-linux-nm-08.png" width="600"
        alt="" />
</p>

11. Pick `eduroam` (or what you named the profile in step 5.) from the list by
    pressing enter on it

> [!WARNING]
> If you chose `Store password only for this user` when setting up the
> connection settings, you may be asked for your password again

<p align="center">
    <img src="images/eduroam-linux-nm-09.png" width="600"
        alt="" />
</p>

12. You should now be connected to the `eduroam` network

<p align="center">
    <img src="images/eduroam-linux-nm-10.png" width="600"
        alt="" />
</p>

13. Exit `nmtui` by choosing `<Back>` and then `Quit` or by pressing escape
    two times
