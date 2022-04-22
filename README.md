# Dark-Souls-3-Reddit-GPT2-bot
Dark Souls 3 Reddit GPT2 bot

Dark Souls 3 is a From Software game known for it's gameplay and atmosphere. Specifically it's known for it's cryptic and exentric NPC dialog. I'm a huge fan of all the FromSoftware Soulsbourne games.

https://en.wikipedia.org/wiki/Dark_Souls_III

Reddit GPT2 Trained reddit bot. Due to the size limitations of the file, I could not upload the trained model, so rather I've attached the text used, and a script on how to finetune a language model on Google Collab using GPT2

Using Google Collab, upload the text file and run the script, which should generate the language model you can download and use. Details (and Credit) in the Training file, I used it, but did create it.

Once you've downloaded the fine tuned GPT2 language model you can use the python jupyter notebook to create a reddit bot that will generate text based on a input (needs GPU) and post to the highests voted comment (which it took as an input)

Note, it is computationally a tad heavy. Final model is about 1G if you use the allowed default 124M GPT2 model, you'll have to pay for Google Collab Pro if you want to use the larger language models, or train it locally.

Uses PRAW to scrape comments and reply to reddit, will need a reddit dev app auth (free) for the API login.

Thank you, was fun training and building the bot. 

If you like to learn more about the NLP model used: 

https://openai.com/

Examples outputs:

https://www.reddit.com/user/FromSoftGameBot/comments/

