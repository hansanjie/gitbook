# Sources

A source is your input for further recordings. The list of Sources looks like this:

![](https://2640386862-files.gitbook.io/\~/files/v0/b/gitbook-legacy-files/o/assets%2F-MWeDSPKGN0gVp2Gooat%2F-MXGfIUdqxTo3qjQvRhl%2F-MXGlinEul-4YD\_pBU7o%2Fimage.png?alt=media\&token=e475f094-fa22-4813-aa6d-14fe67fa0d2d)

By clicking the **Add Source** or the **+** buttons, you can add a new source to the application:

![](https://2640386862-files.gitbook.io/\~/files/v0/b/gitbook-legacy-files/o/assets%2F-MWeDSPKGN0gVp2Gooat%2F-MXGfIUdqxTo3qjQvRhl%2F-MXGm3vbA2HETrwPeJXX%2Fimage.png?alt=media\&token=d34b1df9-44a3-4e4f-9b59-f7d01e6d2ef3)

You can select the type of source:

![](https://2640386862-files.gitbook.io/\~/files/v0/b/gitbook-legacy-files/o/assets%2F-MWeDSPKGN0gVp2Gooat%2F-Mb1Ygp95jFUaA9sdWXK%2F-Mb1\_zrcMXhv6T-oRlD-%2Fimage.png?alt=media\&token=08ce9740-ba30-4230-87e1-9070388deaab)

* Hardware - all the real devices (Decklink, AJA, Bluefish, Magewell, web-cameras, USB-connected devices, etc.).
* NDI - all the NDI sources available on your machine
* VT - feeds from Video Transport
* Network Stream - stream from a public or a local network (RTMP, RTSP, UDP, YouTube, IP cameras, etc.)

Once the type is selected, you can choose the device (or stream):

![](https://2640386862-files.gitbook.io/\~/files/v0/b/gitbook-legacy-files/o/assets%2F-MWeDSPKGN0gVp2Gooat%2F-MXGfIUdqxTo3qjQvRhl%2F-MXGmweIw4FWfTUnSIQY%2Fimage.png?alt=media\&token=daab19e4-e302-44fa-a7d8-1abb801811fb)

For NDI and VT options, when you open the list, Direct Take dynamically refreshes available sources.

Next, you should set a unique source name that you'll see in the Sources list later.

With the video format list, you can set the video format for the device to work with. Most sources (NDI and VT feeds included) support the auto-detection (**Auto/Not Specified**) of the input signal, but for some of them (e.g. Decklink), you can set it specifically:

![](https://2640386862-files.gitbook.io/\~/files/v0/b/gitbook-legacy-files/o/assets%2F-MWeDSPKGN0gVp2Gooat%2F-MXGfIUdqxTo3qjQvRhl%2F-MXGo9XtWLxghxrkHeiO%2Fimage.png?alt=media\&token=1766f475-aa8c-4e13-9388-b4dd89268b2b)

With the input line, you can set for capture devices what lines should be used for the input processing: SDI or HDMI, for example:

![](https://2640386862-files.gitbook.io/\~/files/v0/b/gitbook-legacy-files/o/assets%2F-MWeDSPKGN0gVp2Gooat%2F-MXGfIUdqxTo3qjQvRhl%2F-MXGocn94JPw6U75q7jC%2Fimage.png?alt=media\&token=7c80c7af-1962-4778-af47-cf2e3faaa5f1)

By default, you use the embedded audio with your video source. The Audio list includes external audio sources that you can add to the original embedded audio of your source. For example, you can add your local microphone to the existing NDI feed. If you like to keep just the original audio, choose the **No External Audio** option:

![](https://2640386862-files.gitbook.io/\~/files/v0/b/gitbook-legacy-files/o/assets%2F-MWeDSPKGN0gVp2Gooat%2F-MXGfIUdqxTo3qjQvRhl%2F-MXGpHoSx32v6MM0Tc-\_%2Fimage.png?alt=media\&token=f702103e-8718-460a-9b2a-e5531088636b)

The slider below sets the overall audio gain modification for the source. 0 dB means "keep the original audio gain". Positive values make the audio louder, negative values make the audio quieter.

Here is an example of how a source configuration might look like:

![](https://2640386862-files.gitbook.io/\~/files/v0/b/gitbook-legacy-files/o/assets%2F-MWeDSPKGN0gVp2Gooat%2F-MXGfIUdqxTo3qjQvRhl%2F-MXGptvUCWebbDg3Ubjh%2Fimage.png?alt=media\&token=caedc33c-a185-4d37-86c9-0aa88bc82c2b)

By clicking the **Save Source** button, you add the source to Direct Take. If you'd like to cancel the source configuration you can click the **X** button at the right from the **Source settings**.

Once you have saved the source, it is available in the Sources list:

![](https://2640386862-files.gitbook.io/\~/files/v0/b/gitbook-legacy-files/o/assets%2F-MWeDSPKGN0gVp2Gooat%2F-Mb1Ygp95jFUaA9sdWXK%2F-Mb1aLI6nryxq1Q0l8\_G%2Fimage.png?alt=media\&token=419d1080-fce9-494f-b3fc-3602fb7c9631)

To change the source configuration or to remove the source, you should click the Edit button:

![](https://2640386862-files.gitbook.io/\~/files/v0/b/gitbook-legacy-files/o/assets%2F-MWeDSPKGN0gVp2Gooat%2F-MXGfIUdqxTo3qjQvRhl%2F-MXGrEWwmBSqrkbVA0A2%2Fimage.png?alt=media\&token=f9444482-5a4c-475d-ab29-0d90f00440f5)

After that, the settings menu is open:

![](https://2640386862-files.gitbook.io/\~/files/v0/b/gitbook-legacy-files/o/assets%2F-MWeDSPKGN0gVp2Gooat%2F-MXGfIUdqxTo3qjQvRhl%2F-MXGrTBT8OEdHtFDtqtu%2Fimage.png?alt=media\&token=3eee1e07-0c43-4f1e-9895-6d503d8b9425)

Change the settings, and click the **Save Source** button to implement the changes. If you'd like to cancel the changes, click the **X** button at the top-right corner. To delete the source, click the trash bin button.

For this type of sources, the interface looks like

![](https://2640386862-files.gitbook.io/\~/files/v0/b/gitbook-legacy-files/o/assets%2F-MWeDSPKGN0gVp2Gooat%2F-Mb1Ygp95jFUaA9sdWXK%2F-Mb1acb8JWMc\_Lo8pPZi%2Fimage.png?alt=media\&token=3dc56915-0af2-4b49-9619-721ec68b3115)

where you put a link to the stream in the **Stream URL** field. To improve the stream playback stability, you can set the minimal buffer value. With this setting, the initialization time might be longer but the playback is more stable.
