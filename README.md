# ansi-md
discord ansi markdown formatting guide

## basics

some things to note:
  - all text must be contained inside a code block with the `ANSI` decorator

![what the box should look like](https://cdn.discordapp.com/attachments/973196031158280202/973208120237105212/unknown.png)
![what the image looks like](https://cdn.discordapp.com/attachments/973196031158280202/973208158392688640/unknown.png)
  - to use multiple different text formats in the same code block you must close it off with `[0m` ( = \u001b)
  - formatting not visible to mobile users, will look like a jumbled mess

![looks fucked right?](https://cdn.discordapp.com/attachments/973196031158280202/973207697421914172/unknown.png)

## colored text

colored text is declared through `[{}m` or `[{};1m` where `{}` is a number from 30-37

colors are as seen below

![no witty thing to say here](https://cdn.discordapp.com/attachments/973196031158280202/973209632044634112/unknown.png)

copy paste box
```ansi
[30m ass black[0m
[31mfire red[0m
[32mshitty green[0m
[33mnice orange[0m
[34mepic blue[0m
[35mpoggers pink[0m
[36mgood green[0m
[37mfat white[0m
[30;1mass black 2[0m
[31;1mfire red 2[0m
[32;1mshitty green 2[0m
[33;1mnice orange 2[0m
[34;1mepic blue 2[0m
[35;1mpoggers pink 2[0m
[36;1mgood green 2[0m
[37;1mfat white 2[0m
```

you can also use colored background text, but the options are a bit shite to be honest

you can do that in the same was as above but with numbers in range 40-47

![sex](https://media.discordapp.net/attachments/973196031158280202/973209451437883422/unknown.png)

another copy paste box
```ansi
[40mBlack[0m
[41mOrange[0m
[42mGrey[0m
[43mGrey But Lighter[0m
[44mGrey But Even Lighter[0m
[45mPurple[0m
[46mEven Lighter Grey[0m
[47mWhite[0m
```

colored text combined with the █ (\u2588) character can be used to make simple ANSI art

## alt formatting

text can be made bold through adding `[1m` in front of the text, though the bold is not very visible

![case in point](https://cdn.discordapp.com/attachments/973196031158280202/973211165285052456/unknown.png)

![case in point 2](https://cdn.discordapp.com/attachments/973196031158280202/973211330062479400/unknown.png)

```ansi
sex
[1msex[0m
```

the same thing can be done for underlining text, but with `[4m` instead of `[1m`

![the underline](https://cdn.discordapp.com/attachments/973196031158280202/973211773442355230/unknown.png)

![the underline but not code](https://cdn.discordapp.com/attachments/973196031158280202/973211833781596280/unknown.png)

```ansi
not underlined text
[4munderlined text[0m
```

## multiple on same line

to do multiple different text formats on the same line you have to put a `[0m` between each block

example

![this is a good example](https://cdn.discordapp.com/attachments/973196031158280202/973215877409419345/unknown.png)

```ansi
[31mRED TEXT [0m[34mBLUE TEXT [0m[32mGREEN TEXT [0m[33mYELLOW TEXT[0m
```

## last but not least

you can combine tags to do interesting stuff with the text

example, using underlined and red text

![this is an example](https://cdn.discordapp.com/attachments/973196031158280202/973212617713791056/unknown.png)

```ansi
[4m[31mhehehe[0m
```

another example, this time using orange background and blue text

![example 2](https://cdn.discordapp.com/attachments/973196031158280202/973213857055117372/unknown.png)

```ansi
[34m[41maint this cool?[0m
```

## thats all folks
maybe add my bot to your server while you're here

his name is dick and balls bot and he does stuff (he's a funny guy when you get to know him)

[invite him into your home](https://discord.com/api/oauth2/authorize?client_id=659540200053276685&permissions=2349333568&scope=bot)

![who could resist a face like that?](https://cdn.discordapp.com/avatars/659540200053276685/0498dd70e868b073a76d3f9a6dde199f.webp?size=256)
