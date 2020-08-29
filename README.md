SamplerBox
==========

An open-source audio sampler project based on RaspberryPi.

Website: www.samplerbox.org

![http://gget.it/flurexml/1.jpg](https://www.youtube.com/watch?v=yz7GZ8YOjTw)

[Install](#install)

----

SamplerBox works with the RaspberryPi's built-in soundcard, but it is recommended to use a USB DAC (such as [this 6€ one](http://www.ebay.fr/itm/1Pc-PCM2704-5V-Mini-USB-Alimente-Sound-Carte-DAC-decodeur-Board-pr-ordinateur-PC-/231334667385?pt=LH_DefaultDomain_71&hash=item35dc9ee479)) for better sound quality.

1. Download SamplerBox:

    ```bash
      git clone https://github.com/J-Rios/SamplerBox.git
      cd SamplerBox
    ```

2. Install the required dependencies:

    ```bash
    chmod +x install_requeriments
    sudo ./install_requeriments
    ```

3. Build SamplerBox:

    ```bash
    sudo python setup.py build_ext --inplace
    ```

4. Run the Sampler with `python samplerbox.py`.

5. Play some notes on the connected MIDI keyboard, you'll hear some sound!

*(Optional)*  Modify `samplerbox.py`'s first lines if you want to change root directory for sample-sets, default soundcard, etc.

[How to use it](#howto)
----

See the [FAQ](http://www.samplerbox.org/faq) on www.samplerbox.org.

[ISO image](#isoimage)
----

The ready-to-use ISO images available on [www.samplerbox.org](http://www.samplerbox.org) are built with the help of a script that can be found in `isoimage/samplerbox_iso_maker.sh`.

[About](#about)
----

Author : Joseph Ernest (twitter: [@JosephErnest](http:/twitter.com/JosephErnest), mail: [contact@samplerbox.org](mailto:contact@samplerbox.org))

[License](#license)
----

[Creative Commons BY-SA 3.0](http://creativecommons.org/licenses/by-sa/3.0/)
