# Eduroam connection guide - UNSTPB

## Within UNSTPB

### On Android

The images in this section are for Samsung devices. Your device's interface
may vary. (See the [`images`](images/) folder for screenshots for other manufacturers)

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
