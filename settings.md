# Talk 11 Settings

Talk 11 includes a variety of settings needed to make the plugin work.

## API Key
You'll need an API key from Eleven Labs to make the plugin work, with this found inside your settings at Eleven Labs. 

Your Eleven Labs API key **is not** your Talk 11 purchase code. Rather, you need an account at Eleven Labs and an API key from your settings. Once that has been connected and saved (Save Changes), our settings screen will report back whether your API key is valid and working. 

## Default Voice
Once your API key is linked up, the voices loaded in your library will be loaded with it. 

These could be the standard variety assigned to your Eleven Labs kit, and dependent on the Eleven Labs plan you're subscribed to, it could also be your own voice. 

The default voice setting will designate the voice in your post options that it will automatically default to. You can change that on a post-by-post basis, but this is the setting for the first voice you'll see on each post editor page.

## AI Model
A setting specific to the settings screen, this allows you to select the AI model for the voice processing.

Two are included at present: 
- Eleven Turbo V2
- Eleven Multilingual V2

### Eleven Turbo V2
The recommended model for most things, Eleven Turbo is a little less expensive to run, though the results aren't typically as realistic for your personal voices. 

If you're using some of the pre-made voices, Turbo should be fine for most things. 

### Eleven Multilingual V2
A more realistic voice setting, this one costs a little more to run, but gets really great results when you've uploaded your own voice. 

It costs more in your credits, so be aware that it'll eat into your monthly token amount, but the results are really solid. It's what I use for my sites with Talk 11. 

## Player Position
You'll ideally want a player on your page, and for that, we have positions we've built in CSS ahead of time. 

They include:
- Disabled (Use shortcode or block)
- Before content
- After content
- Top of content on mobile only

### Disabled

If you want to manually control where the element goes, disable the automatic injection using this option, and instead insert the player using a shortcode or a block. 

### Before content

If you want someone to listen to the content **before** they have the option to read your content -- which is where most listen players go -- this option will insert the audio player at the top of the content on both mobile and desktop renders.

### After content

Would you prefer it if people were offered a chance to listen  **after** the content ends? That's what this option does, inserting it on both mobile and desktop renders at the end of the content.

### Top of content on mobile only

This one is pretty self-explanatory: it'll insert the automatic player at the top of the content only on mobile viewports, allowing you to add the desktop element through another aspect, such as via a sidebar. 

## Player Heading

The text that goes before the audio player on inserts. Change it to whatever you want. 

## Auto Generate
Select this setting if you want all new content to automatically generate the audio file on each post.

You might not *want* to have every article turn into a spoken file. Depending on how much you have, it can get costly. If that's the case, leave it unchecked (it is by default). 

## Exclude Quote Paragraphs

Some content can also be ignored when sent to Eleven Labs, such as paragraphs beginning with a quote. When this box is checked, Talk 11 will ignore paragraphs beginning with a quotation mark, but include all others, including paragraphs with a quote mentioned later on.

Typically, paragraphs beginning with a quotation mark are said by someone else. Checking this feature will remove those lines from the spoken text. 

By default, this is left unchecked. 

## Error Log

Errors can and will happen. Not everything will hum along perfectly, so for that, we have an error log. You probably won't need to use this, but if an error occurs, you'll find a note about what happened here. 