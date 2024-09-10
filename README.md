# 🍥 Inversed — Anime Recommendation Backwards 🍥
### _Have you ever watched so much anime that you don't know what to watch next?_

Fret not, fellow weebs! We’ve got just the quirky solution to spice up your anime recommendation game! 🎉 Presenting **Inversed-Anime_Recs**, your new favorite anime matchmaker, powered by not one, but TWO awesome APIs working in perfect harmony to bring you unique anime suggestions, quotes, and more.✨ 

## 🌸 What Is This All About?
**Inversed-Anime_Recs** combines the power of **Jikan API** and **AnimeChan API** to give you a delightful experience of random anime quotes AND anime recommendations based on those quotes. Tired of watching mainstream shows? Let your next anime find *you* through the wisdom of quotes! 🎬💬

- **Jikan API** (Unofficial MyAnimeList API) fetches detailed anime information like the title, synopsis, rating, and more.
- **AnimeChan API** pulls random anime quotes from an endless pool of shows, giving you a glimpse of an anime world you may not have explored.

Together, these APIs create a fun combination to help you discover new anime based on the random quotes.

## 🎯 Why These APIs?
- **Jikan API** was chosen because it provides rich and structured data for any anime. Plus, no API key is required (woohoo!). There's also a great rate limit of 3 requests per second.
- **AnimeChan API** gives us some seriously cool anime quotes. While it does have a rate limit of 20 requests per hour, that's not too bad because who is watching 20 animes per hour 😂

## 🔧 How to Use This Feature?
Super easy! You don’t need any fancy setup; just follow these steps to get started:

1. **Clone this repo** to your local machine.
2. Make sure you have `requests` installed in your environment (`pip install requests`).
3. Run the cell with all the necessary imports (`requests, textwrap, and IPython.display`)
3. Run the next cell under **Jikan & Animechan API** and watch the magic unfold! 🎇

The feature works like this:
- The script fetches a **random anime quote** using AnimeChan API.
- It then automatically uses the **anime name** provided alongside the quote to fetch detailed **anime data** using the Jikan API.
- You'll then get an **anime card** with the title, type, synopsis, rating, and year so that you can decide if you'd like to watch the anime! 😊

## 🛠️ Setup
To set this up, you'll need:
- Python 3.x installed on your machine.
- Internet connection to call the APIs.
- No API keys are required for either of the APIs (Yay for simplicity & opensource 🙌).

Install the necessary Python dependencies:
```bash
pip install requests
```

## 💻 Running the Script
Once you’ve got everything set up:
1. **Run the cell** and it will:
   - Fetch a **random quote** from a random anime.
   - Display the **quote** along with the **character name** and **anime title**.
   - Fetch the **anime data** based on the title from Jikan API.
   - Present you with an **anime card** that includes a picture, synopsis, and more!

## 🛡️ Important Notes
- **Rate Limits:** 
  - Jikan API: 3 requests per second, no daily limit.
  - AnimeChan API: 20 requests per hour (be mindful!).
  
- Since the APIs work together as a cohesive function, you’ll have to wait after getting 20 quotes to get more recommendations. 😉

## 💡 Example
**Here’s what you might see when running the script:**

*Your random anime quote is:* <br>
*"Sometimes you have to let go of your pride and let yourself cry."*<br>
*— Edward Elric*<br>

*Wanna know where this is from? Let me fetch the anime data for you:*

![Alt Text](https://miro.medium.com/v2/resize:fit:1400/1*10sQCBzHcWFfPS6Lxl3VhQ.jpeg)
*Anime Title: Fullmetal Alchemist: Brotherhood* <br>
*Type: TV* <br>
*Synopsis: In this world, there exists the alchemical art of transmutation, allowing...* <br>
*Rating: PG-13* <br>
*Year: 2009*


### 🎉 Enjoy the randomness! 🎉

