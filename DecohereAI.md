# Round 3: Decohere AI
[Decohere AI](https://www.decohere.ai/) is an online AI tool that **generates images and video** in response to user prompts. Notably, use is limited to **1000 image prompts + 10 video prompts a month.**

Foremerly known as Decoherence.co, *decohere* is a new UW startup backed by Y Combinator, featuring realtime image prompts.


| Media       | Text | Image      | Video        |
|-------------|------|------------|--------------|
| Supported?  | No   | Yes        | Yes          |
| Rating      | 0    | 5          | 3            |
| Time needed | N/A  | 30 minutes | 30 minutes   |

## Getting Started
To start using the tool:
1. Go to https://www.decohere.ai/
2. Click 'Login' and made a new account (Signup with Google)
3. Follow their tutorial
4. Start with image prompts
5. Optional: set image size (Wide, Square, or Tall)

Clicking the + button (Add to Library) will save the image at the bottom of the page where you can download it. A saved image can then be hearted to be added to your Favorites tab.

## Image Prompts
Let's start with the most successful prompt from Round 2's image generating.

*Image Prompt #1*:
* "Happy athlete wearing a smartwatch"
>![one watch, holding a phone](./images/decohereAI/hawasw.jpeg)

This inital image is okay, but I count three smartwatches which is definitely too many.

I saw many images flash past as I typed in my prompt, but it ended on this one. You can also click left and right to see other generated images from the same prompt. I am clicking left to cycle through those images and see if it eventually cycles back to the original or generates new ones. I have cycled left 7 times and I will conclude that it does not circle back to the original.

>![man, two watches](./images/decohereAI/hawasw2.jpeg)
![woman, two watches](./images/decohereAI/hawasw3.jpeg)
![woman, one watch](./images/decohereAI/hawasw4.jpeg)
![woman, one watch](./images/decohereAI/hawasw5.jpeg)
![man, blue, two watches](./images/decohereAI/hawasw6.jpeg)
![man, red, two watches](./images/decohereAI/hawasw7.jpeg)

All images appear to be track runners, both male and female, mainly white so far. (This suggests some bias in their training data.) Their poses can be slightly strange, somewhere between in action running down the track and posing for the picture. The main critique is that on most of them, they are actually wearing more than one smartwatch. (When I specified “a” meaning only one in the prompt).

I think I saw better ones before, so I might take away the “smartwatch” part or see if it knows “fitness tracker”.

Let’s also try changing the default image options.

*Image Prompt #2*:
* "Happy athlete wearing a fitness tracker"
* Image size: Square (1:1, Instagram, etc.)
>![one watch, holding a phone](./images/decohereAI/hawaft.jpeg)

There were disappointing results when I first typed in the prompt (no real signs of a fitness tracker and possibly multiple arms in a side picture). But surprisingly, there were much better results once I changed the frame to Square.

Perhaps it really does know what a fitness tracker is better than a smartwatch in terms of an athletics context.

I am satisfied with these images, but with a monthly limit of 1000 images a month (as of time of writing), I am much more confident in my ability to test different prompts.

This time I cycle right. I am curious if I can go back to the left and grab the initial picture on the left? Apparently, I can. That is nice. Being able to simply click on the next available image is kind of fun.

>![one watch, holding a phone](./images/decohereAI/hawaft2.jpeg)
![one watch, holding a phone, front](./images/decohereAI/hawaft3.jpeg)
![one watch, running](./images/decohereAI/hawaft4.jpeg)
![two watches, running](./images/decohereAI/hawaft5.jpeg)
![one watch, pose](./images/decohereAI/hawaft6.jpeg)
![one watch, action](./images/decohereAI/hawaft7.jpeg)
![one watch, action](./images/decohereAI/hawaft8.jpeg)

On closer inspection it appears that a double watch is still appearing.

Next, I’m interested to see if results change if I select the Tall image frame.

*Image Prompt #3*:
* "Happy athlete wearing a fitness tracker"
* Image size: Tall (9:16, Tiktok, etc.)
>![one watch, action](./images/decohereAI/hawaftTALL.jpeg)
![strange hand, tag](./images/decohereAI/hawaftTALL2.jpeg)
![two watches, tag](./images/decohereAI/hawaftTALL3.jpeg)

Entirely new images are generated when switching frames. The page must be zoomed out to see your saved images.

Looking at the new images, you can see the picture tag used when in a photoshoot. (I know from experience since I’ve taken part of one before for a study). Apparently the model has captured that tag, which is an interesting mistake.

Let’s go back to simply “happy athlete.”

*Image Prompt #4*:
* "Happy athlete"
* Image size: Wide (16:9, Youtube, etc.)
>![happy athlete](./images/decohereAI/Happyathlete.jpeg)
![happy athlete, two](./images/decohereAI/Happyathlete2.jpeg)

We get roughly the same images of track runners across all frame sizes.

Time spent: 30 minutes.

## Video Prompts
Let’s get a picture saved in the Favorites tab and try generating a video from it.

1.	Go to the Favorites tab
2.	Click on a picture
3.	Select “Reuse image”
4.	Leave Camera Motion at the default (5.0)
5.	Click Generate Video
6.	Wait for the Queue

Upon refreshing the page, I see the generated output under the all tab.

*Video Prompt #1*:
* (Used a picture from Image Prompt #2)
  
https://github.com/Aaron-Thai/GenAI/assets/91993827/2424135c-8d5f-4aa6-887f-2af161ff02cb

The video is surreal as the hand moves and fades out of existence. The static pose has been animated to become laughter, which is novel. Under the free plan the videos are 4 seconds. 

I will try more video generations, gradually speeding up the Camera Motion from 0 to 10. Also, I will also try different pictures.

*Video Prompt #2*:
* (Used a picture from Image Prompt #2)
* Camera Motion: 0.0



The video doesn’t contain much movement. Results are as expected.

*Video Prompt #3*:
* (Used a picture from Image Prompt #2)
* Camera Motion: 1.0



There is some slow panning in the video, which is nice.

*Video Prompt #4*:
* (Used a picture from Image Prompt #3)
* Camera Motion: 3.0



There is some body movement but no mouth movement.

*Video Prompt #5*:
* (Used a picture from Image Prompt #3)
* Camera Motion: 10.0



The static pose has been animated into a running motion, but the face shape morphs and changes halfway through the video, which is a little scary.

*(Between the time of testing and writing, Decohere has added a new feature in their Paid plans to "Use reference person" to generate more consistent images. Perhaps this addresses the issue?)*

Lastly, I'll try generating a new image and then generate a video directly from the result image screen. All the previous images were generated from saved images.

Let's start with a new image prompt.

*Image Prompt #5*:
* "Benefits and challenges of fitness trackers"
* Image size: Wide (16:9, Youtube, etc.)
>![two watches](./images/decohereAI/bacoft.jpeg)
![watch and phone](./images/decohereAI/bacoft1.jpeg)
![watch, running](./images/decohereAI/bacoft2.jpeg)
![running on the phone](./images/decohereAI/bacoft3.jpeg)

Now let's turn the last image into a video.

*Video Prompt #4*:
* (Used a picture from Image Prompt #5)
* Camera Motion: 5.0



The output turned out okay. The video appears to be in slow motion, but the model seemes to be tuned for the default value of 5.0

## Overall Rating: 3/5
*Decohere* is a generative AI currently marketed towards animated video content, but the free trial restricts access to the most in-depth video tools. Thus, the main strength of this tool at a free tier is the straightforward image generation functionality.

In terms of video generation, the term **Camera Motion** is somewhat self-explanatory, referring to the overall movement in the resulting video, whether that is panning of movement from any characters on screen. Adjustment of this setting required some experimentation before satisfactory output was generated. 

### Image Generation: 3/5
The tool delivers realistic flexbility when provided custom prompts, although not consistently. The 1000 monthly prompt limit also enables further testing with different prompts. The ability to cycle through different images is convenient, but images to not change much once a prompt is typed in.

### Video Generation: 1/5
The tool offers access to brief 4 second animations of static images, which is novel but seems more geared towards usage of stock images rather than people speaking. Realistic video generation of moving people is currently a weakpoint of this tool at free tier, but I would expect significantly enhanced performance on a paid plan.

### Bias: ?/5
One of the most interesting things a person can do with this tool is immedaitely see the bias in the generated images as they type in the prompt, as the images update in realtime with the written prompt.

As demonstrated above, the prompt **"happy athlete"** mainly returns pictures of darker skinned people running in track uniform, suggesting that as the basis for their data. However, once fitness trackers are added into the prompt, such as **"happy athlete wearing a fitness tracker,"** the skin tone of people in the generated images becomes considerably lighter as demonstrated above. Again, this exposes the data the AI model was trained on. 

However, collected data can also reflect societal conditions possibly suggesting that: 
1. Certain demographics of people are more likely seen celebrating victory at global track competitions
2. Certain demographics of people are more likely seen wearing fitness trackers

It is more difficult to formulate a bias score as we have not yet agreed upon what constitutes an acceptable level of bias. As this tool still in its early stages, is it possible that biases can be smoothed out as more data is added into the model.






