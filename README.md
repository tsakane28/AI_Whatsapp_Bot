## AI WhatsApp Bot

A conversational AI bot for WhatsApp built using Node.js, WhatsApp-web.js, and Google Generative AI. This bot interacts with users via WhatsApp and generates intelligent responses based on user input.

## Features

- **WhatsApp Integration**: Seamlessly communicate with users through WhatsApp.
- **Generative AI Model**: Utilizes Google Generative AI for generating contextual and human-like responses.
- **QR Authentication**: Easy-to-use QR code-based login.
- **Automatic Replies**: Replies to `.bot` queries with AI-generated responses.

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/AI_Whatsapp_Bot.git
   ```
   
2. Navigate into the project directory:
   ```bash
   cd AI_Whatsapp_Bot
   ```

3. Install the necessary dependencies:
   ```bash
   npm install
   ```

4. Set up your Google Generative AI API key by replacing the key in `bot.js`:
   ```js
   const genAI = new GoogleGenerativeAI('YOUR_API_KEY');
   ```

5. Start the bot:
   ```bash
   node bot.js
   ```

## Usage

- After setting up the bot, scan the QR code with WhatsApp to log in.
- Send messages with `.bot` followed by a prompt to receive an AI-generated reply.
  Example: `.bot What is the weather today?`

## Project Structure

```
AI_Whatsapp_Bot/
│
├── bot.js                  # Main bot logic
├── package.json            # Project metadata and dependencies
├── .gitignore              # Git ignore file
└── README.md               # Project documentation
```

## License

This project is licensed under the MIT License. See the [LICENSE](#license) file for details.

## Contributing

Contributions are welcome! If you would like to contribute to this project, please create a pull request with a description of your changes.

## Contact

For any issues, feel free to reach out to me:
- **GitHub**: [Tsakane Shiri](https://github.com/tsakane28)
- **Email**: wesleytsakane116.email@gmail.com
```

### 2. **Add MIT License**

Create a new file in your project root called `LICENSE` and add the following text:

```markdown
MIT License

Copyright (c) 2024 Tsakane Shiri

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

### 3. **Commit the changes**

Add the `README.md` and `LICENSE` files to your Git repository, commit, and push:

```bash
git add README.md LICENSE
git commit -m "Added README and MIT License"
git push origin main
```
