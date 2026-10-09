# Eduroam connection guide - UNSTPB

## Within UNSTPB

### On Android

The images in this section are for Samsung devices. Your device's interface
may vary. (See the [`images`](images/) folder for screenshots for other manufacturers)

> [!WARNING]
> If you have previously tried to connect to the `eduroam` network, first
> forget the `eduroam` network and then follow this guide.

1. Pick the `eduroam` network in your Wi-Fi settings.

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
