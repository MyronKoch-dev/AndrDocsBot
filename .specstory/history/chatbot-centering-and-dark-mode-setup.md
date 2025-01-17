## SpecStory

## Chatbot Centering and Dark Mode Setup (1/17/2025, 4:08:49 PM)

_**User**_

Center the content of this bot, and put it in dark mode. 

---

_**Assistant**_

I'll help you modify the HTML file to center the chatbot content and implement a dark mode theme. I'll edit the styles and theme configuration.

---

_**Assistant**_

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Flowise Chatbot</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: #1a1a1a;
        }
        #chatbot-container {
            width: 90%;
            max-width: 1200px;
            height: 90vh;
            margin: auto;
        }
    </style>
</head>
// ... existing code ...
            theme: {
                button: {
                    backgroundColor: '#3B81F6',
                    right: 20,
                    bottom: 20,
                    size: 48,
                    dragAndDrop: true,
                    iconColor: 'white',
                    customIconSrc: 'https://raw.githubusercontent.com/walkxcode/dashboard-icons/main/svg/google-messages.svg',
                    autoWindowOpen: {
                        autoOpen: true,
                        openDelay: 2,
                        autoOpenOnMobile: false
                    }
                },
                tooltip: {
                    showTooltip: true,
                    tooltipMessage: 'Hi There 👋!',
                    tooltipBackgroundColor: '#2d2d2d',
                    tooltipTextColor: 'white',
                    tooltipFontSize: 16
                },
                disclaimer: {
                    title: 'Disclaimer',
                    message: "By using this chatbot, you agree to the <a target=\"_blank\" href=\"https://flowiseai.com/terms\">Terms & Condition</a>",
                    textColor: 'white',
                    buttonColor: '#3b82f6',
                    buttonText: 'Start Chatting',
                    buttonTextColor: 'white',
                    blurredBackgroundColor: 'rgba(0, 0, 0, 0.6)',
                    backgroundColor: '#2d2d2d'
                },
                customCSS: ``,
                chatWindow: {
                    showTitle: true,
                    showAgentMessages: true,
                    title: 'Flowise Bot',
                    titleAvatarSrc: 'https://raw.githubusercontent.com/walkxcode/dashboard-icons/main/svg/google-messages.svg',
                    welcomeMessage: 'Hello! This is a custom welcome message',
                    errorMessage: 'This is a custom error message',
                    backgroundColor: '#1a1a1a',
                    backgroundImage: '',
                    height: '100%',
                    width: '100%',
                    fontSize: 16,
                    starterPrompts: [
                        "What is a bot?",
                        "Who are you?"
                    ],
                    starterPromptFontSize: 15,
                    clearChatOnReload: false,
                    sourceDocsTitle: 'Sources:',
                    renderHTML: true,
                    botMessage: {
                        backgroundColor: '#2d2d2d',
                        textColor: '#ffffff',
                        showAvatar: true,
                        avatarSrc: 'https://raw.githubusercontent.com/zahidkhawaja/langchain-chat-nextjs/main/public/parroticon.png'
                    },
                    userMessage: {
                        backgroundColor: '#3B81F6',
                        textColor: '#ffffff',
                        showAvatar: true,
                        avatarSrc: 'https://raw.githubusercontent.com/zahidkhawaja/langchain-chat-nextjs/main/public/usericon.png'
                    },
                    textInput: {
                        placeholder: 'Type your question',
                        backgroundColor: '#2d2d2d',
                        textColor: '#ffffff',
                        sendButtonColor: '#3B81F6',
                        maxChars: 50,
                        maxCharsWarningMessage: 'You exceeded the characters limit. Please input less than 50 characters.',
                        autoFocus: true,
                        sendMessageSound: true,
                        sendSoundLocation: 'send_message.mp3',
                        receiveMessageSound: true,
                        receiveSoundLocation: 'receive_message.mp3'
                    },
                    feedback: {
                        color: '#ffffff'
                    },
                    dateTimeToggle: {
                        date: true,
                        time: true
                    },
                    footer: {
                        textColor: '#ffffff',
                        text: 'Powered by',
                        company: 'Flowise',
                        companyLink: 'https://flowiseai.com'
                    }
                }
            }
// ... existing code ...
```

---

_**Assistant**_



I've made the following changes to implement dark mode and center the content:

1. Centered the content:
   - Added `width: 90%` and `max-width: 1200px` to the chatbot container
   - Added `margin: auto` to center the container
   - Set `height: 90vh` to give some padding on top and bottom

2. Implemented dark mode:
   - Changed the background color to a dark gray (`#1a1a1a`)
   - Updated all text colors to white for better contrast
   - Changed message backgrounds to darker shades
   - Updated the tooltip and disclaimer backgrounds to match the dark theme
   - Modified the input field to have a dark background with white text

The chatbot should now be centered on the page with a dark theme that's easier on the eyes. All the interactive elements maintain good contrast ratios for accessibility.

---



---

