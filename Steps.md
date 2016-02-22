**getting cyko**
> download cyko here -> http://code.google.com/p/cyko/downloads/list
**installing cyko**
> guide to install it is here -> http://code.google.com/p/cyko/wiki/Installation

**encoding with cyko**

![https://lh4.googleusercontent.com/--BgMKlasPAw/TvfPgzLFaMI/AAAAAAAAAHs/PU5eE1heFMo/s800/Cyko_S1.png](https://lh4.googleusercontent.com/--BgMKlasPAw/TvfPgzLFaMI/AAAAAAAAAHs/PU5eE1heFMo/s800/Cyko_S1.png)

![https://lh3.googleusercontent.com/-vYXH-XEyT3s/TvztUzC_u9I/AAAAAAAAAJU/VSFf_Ko9slM/s800/Cyko.2.1.png](https://lh3.googleusercontent.com/-vYXH-XEyT3s/TvztUzC_u9I/AAAAAAAAAJU/VSFf_Ko9slM/s800/Cyko.2.1.png)

Notes:

**Rate Control**
> Target Quality choose from 25-30 for example on "**Value**" inputbox set 26
    * the higher the quality value the lower the quality but lower the file size
> Target Bitrate choose from 300-500 for example on "**Value**" inputbox set 400
    * the higher the bitrate value the higher the quality but higher the file size
**Height**
> choose from 400, 480, 576 (this is 400p, 480p, 576p)
    * cyko (specifically Handbrake) do not allow upscaling so if your source is not 720p for example once you set 720p on the "Height" inputbox it will be automatically set to the actual height pixel resolution of the source
    * you can switch this to **Width** if you like

**Audio Bitrate**
> choose from 48-99 for example 48 is the recommend choice
    * the higher the audio bitrate the higher the quality but higher the file size

**Hard Subs**
> if its unchecked then it will do Soft Subs
  * if "**Hard Subs**" is checked it will output to mp4, you may wonder what if the source file has no subs at all so will checking "Hard Subs" still output to mp4? the answer is yes
  * if "**Hard Subs**" is unchecked it will output to mkv, and will add all the soft subs to mkv

**Denoise**
> check this always because removal of noise on the video like grains will lessen the final filesize more

**Presets**
> always go for "**Very Slow**", its much slower encoding or will give you longer encoding time but at the benefit of more lower filesize output

**Tunes**
> always go for "**Animation**" if your source is Anime/Cartoons, if your video input is live-action or 3D or CGI or real-life footages then go for "**Film**"

**Profiles**
> always go for "**High**" if your targeting playback on PC or laptops, "**Main**" is almost the same in terms of power consumption with "**High**" profile, while "**Baseline**" profile is mainly for low power playback devices such as mobile phones

![https://lh3.googleusercontent.com/-sikNB5kOmR4/TvfPhc_eUjI/AAAAAAAAAH0/qNzQUi1pioQ/s800/Cyko_S3.png](https://lh3.googleusercontent.com/-sikNB5kOmR4/TvfPhc_eUjI/AAAAAAAAAH0/qNzQUi1pioQ/s800/Cyko_S3.png)

NOTE: if ever you are prompted by this message box

![https://lh4.googleusercontent.com/-5UjV28ky6rM/TvfB5yNx_4I/AAAAAAAAAHU/mDpQvYKaf-Y/s800/Cyko.7.jpg](https://lh4.googleusercontent.com/-5UjV28ky6rM/TvfB5yNx_4I/AAAAAAAAAHU/mDpQvYKaf-Y/s800/Cyko.7.jpg)

it means that you should place HandbrakeCLI.exe on the same place Cyko is in so check the "installing cyko" section at the top of this guide again

and that is all folks, congrats on re-encoding