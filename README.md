# Alumni Sans Inline

Alumni Inline is a stand alone font from its base font, Alumni Sans (a variable font). Inline is a black weight designed to be used as a display font above 72pt in print (assuming 300 dpi) and above 72px in digital media. 

In situations that require large text, use it in combination with the Alumni Sans base design.


![Sample Image](documentation/image1.png)

## Building the Fonts

The font is built using fontmake and gftools post processing script. Tools are all python based, so it must be previously installed.

To install all the Python tools into a virtualenv, do the following:

From terminal:

```

cd your/local/project/directory

#once in the project folder create a virtual environment. 
This step has to be done just once, the first time:

python3 -m venv venv

#activate the virtual environment

source venv/bin/activate

#install the required dependencies

pip install -r requirements.txt

```

Then run the this command:

```
cd sources
gftools builder config.yml
```

## Changelog

**8 Dec 2021. Version 1.018**
- SIGNIFICANT GF Latin Plus added.


## License

This Font Software is licensed under the SIL Open Font License, Version 1.1.
This license is copied below, and is also available with a FAQ at
https://scripts.sil.org/OFL