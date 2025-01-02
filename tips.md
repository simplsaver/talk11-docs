# Tips & Tricks

I built Talk 11 to make content easier to consume, and to make a talkie file on my website sound more like me. Not *just* another AI voice, but one that could sound like the writer and journalist building post and story. 

However, there are some tips and tricks you can use to make Talk 11 work better overall. 

## Talk 11 block

One is to use the Talk 11 block, meaning you can easily integrate a player with your sidebar on a page by page basis.

An optional mechanism, you can trigger the Talk 11 block to load anywhere where blocks are supported, affording you control to load the text 

## Check whether a post has audio from the post screen

Depending on how much content you have, I wanted to have an easy way to track whether an audio file was attached. So I implemented one.

From the post listing, you'll see a red or green light for whether there's an audio file attached. If the light is green, audio is active. If it's red, there is none. It's pretty easy to work out. 

## Skip over quotes

Content can sound a little strange if you read it the way it was written, particularly if "the way it was written" includes quotes the writer didn't actually say. Such as when quotes are used. 

In article and story writing, quotes are typically used as follows:

>"The person said something," said John Doe. "He wasn't sure about the result."

If you check the "Exclude Quote Paragraphs" option in settings, that paragraph would be ignored when a talk file is requested. If left unchecked, it would be left included. 


>[!IMPORTANT] Some quotes will be rendered
>
>It's worth noting, however, that if the quote began outside of the beginning of a paragraph, it would still be included. 
>
>The quote would be included if that same quote read as:
>
>>John Doe said "the person said something. He wasn't sure about the result."
>
>If you plan on having quotes removed from audio files, make sure the quotation mark begins in a paragraph where they are mentioned. 

## Some errors are just you needing to wait

Believe it or not, some errors appear to be simply down to us needing to be more patient. Whether it's a timeout problem or a delay between servers, we've found that some errors reported in the post interface will actually resolve minutes later if you save the post (draft or published), and come back to the post in five or ten minutes.

One way to check whether an audio files has successfully generated is to check your log in Eleven Labs. That will tell you whether a voice has successfully received a request to generate, and what it sounds like. If it can be found in the Eleven Labs log, your Wordpress instance should have the file, as well. 

This is typically an issue on larger articles, particularly those over 1000 words long. 