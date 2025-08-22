# MemoDesk User Guide

**A simple, powerful AI assistant for your desktop that keeps your conversations and knowledge organized.**

MemoDesk combines the best of both worlds: you can run AI models directly on your computer for privacy, or connect to cloud AI services for more power. Everything you discuss gets saved and organized so you can find it later.

---

## Quick Start

### What You'll Need
- Mac computer (macOS 10.15 or newer)
- At least 8GB of memory (16GB better if using local AI)
- 10GB of free storage space
- Internet connection (optional if you only use local AI)

### First Time Setup

When you first open MemoDesk, you'll see a simple setup wizard:

1. **Choose where to save your conversations** - Pick a folder on your computer
2. **Select your AI assistant** - Choose between local (runs on your computer) or cloud-based AI
3. **Pick a personality** - Decide how you want your AI to behave
4. **Set privacy level** - Choose how much internet access to allow

That's it! You're ready to start chatting with AI.

---

## Understanding the Interface

### The Main Screen

MemoDesk has a clean layout with these main areas:

- **Left sidebar**: Quick controls and navigation
- **Chat area**: Where you talk with AI (can split into two panels)
- **Top tabs**: Switch between Chats, Memories, Settings, and this Guide

### Key Controls
- **Theme button**: Switch between light and dark mode
- **AI selector**: Choose which AI assistant to use
- **Split view**: Talk to two different AIs at once
- **Memory button**: Access your saved conversations and notes

---

## Chatting with AI

### Basic Conversations

**What it does**: Have natural conversations with AI that get automatically saved.

**How to do it**:
1. Type your question in the text box at the bottom
2. Press Enter or click Send
3. Wait for the AI's response
4. Continue the conversation naturally

**Tips**:
- Be specific in your questions for better answers
- Your conversation saves automatically every few messages
- You can scroll up to see your chat history anytime

### Using Two AIs at Once

**What it does**: Compare responses from different AI models or have specialized conversations.

**How to set it up**:
1. Click the split-screen button (looks like two rectangles)
2. Choose a different AI for the right panel
3. Type in either panel to chat with that AI
4. Or use "shared input" mode to send the same message to both

**When this helps**:
- Comparing different AI responses
- Using one AI for creative tasks, another for factual questions
- Getting a second opinion on complex topics

---

## Managing Your AI Models

### Using Cloud AI Services

**What it does**: Connect to powerful online AI services like ChatGPT, Claude, or others.

**How to set it up**:
1. Go to Settings
2. Click on "Cloud Models"
3. Choose your preferred service (OpenAI, Anthropic, etc.)
4. Enter your API key (you'll need to get this from the AI service's website)
5. Select which specific model to use

**Pros**: Very powerful, no impact on your computer's performance
**Cons**: Requires internet, costs money, sends your data to external services

### Using Local AI Models

**What it does**: Run AI directly on your computer for complete privacy.

**How to set it up**:
1. Download AI model files (GGUF format) to a folder on your computer
2. Go to Settings → Local Models
3. Point MemoDesk to your model folder
4. Select a model and click Start
5. Wait for it to load (this can take a few minutes)

**Pros**: Completely private, no ongoing costs, works without internet
**Cons**: Uses your computer's memory and processing power, slower responses

**Troubleshooting**:
- If a model won't start, try restarting MemoDesk
- Check that no other AI apps are using the same model
- Larger models need more memory - try a smaller model if you're having issues

---

## Organizing Your Memories

### What Are Memories?

**Memories** are your saved conversations, notes, and important information. Think of it as your personal AI knowledge library.

### Saving Conversations to Memory

**Automatic saving**: Most conversations save automatically
**Manual saving**: 
1. Right-click on any message
2. Choose "Save to Memory"
3. Add tags or notes if you want
4. Choose which folder to save it in

### Finding Old Conversations

**Search everything**:
1. Go to the Memories tab
2. Type keywords in the search box
3. Use filters to narrow by date, type, or tags

**Browse by folders**:
1. Click through your memory folders
2. Each conversation shows a preview
3. Click to open the full conversation

### Organizing Your Memories

**Create folders**:
1. Right-click in the Memories area
2. Choose "New Folder"
3. Name it something descriptive (like "Work Projects" or "Research")

**Add tags**: When saving, add keywords that describe the content
**Clean up regularly**: Delete conversations you no longer need

---

## Customizing Your AI Assistant

### Choosing a Personality

**What it does**: Changes how your AI responds - formal vs casual, creative vs factual, etc.

**How to change it**:
1. Click the persona selector in the sidebar
2. Choose from built-in options like "Professional," "Creative," or "Researcher"
3. Your AI will immediately start using that style

### Creating Custom Personalities

**For advanced users**:
1. Go to Settings → Personas
2. Click "Create New"
3. Write instructions for how you want the AI to behave
4. Test it out and adjust as needed

**Ideas for custom personas**:
- A writing coach that gives specific feedback
- A patient teacher for learning new topics
- A brainstorming partner for creative projects

---

## Privacy and Security Features

### Airgap Mode (Maximum Privacy)

**What it does**: Completely cuts off internet access for ultimate privacy.

**When to use**: Working with confidential information, classified data, or when you need absolute privacy.

**How to enable**:
1. Go to Settings → Security
2. Toggle "Airgap Mode" on
3. Restart MemoDesk
4. Only local AI models will work in this mode

### Offline Mode (Limited Internet)

**What it does**: Blocks cloud AI services but allows app updates.

**How to enable**:
1. Settings → Security
2. Toggle "Offline Mode" on
3. You can still use local models and update the app

### Password Protection

**Setting up**:
1. Settings → Security
2. Set a master password
3. Choose when to require it (startup, after idle time, etc.)

---

## Common Tasks

### How to Recover a Lost Conversation

1. Go to the Memories tab
2. Check the "Recent" folder first
3. Try searching for keywords from the conversation
4. Check the Trash folder - deleted items stay there for 30 days
5. If it was recent, check your active tabs - it might still be open

### How to Export Your Data

1. Settings → Data Management
2. Choose "Export Memories"
3. Select what to export (all conversations, specific folders, date ranges)
4. Choose your format (text files, PDF, etc.)
5. Pick where to save the files

### How to Fix "AI Not Responding" Issues

**For cloud AI**:
1. Check your internet connection
2. Verify your API key is still valid
3. Check if you've hit usage limits
4. Try switching to a different model

**For local AI**:
1. Check if the model is still running (Settings → Local Models)
2. Restart the model if it shows as stopped
3. Try a smaller model if you're running out of memory
4. Restart MemoDesk if problems persist

### How to Free Up Storage Space

1. Go to Memories tab
2. Sort by size or date
3. Delete large, old conversations you don't need
4. Empty the Trash folder
5. In Settings, reduce how long conversations are kept in auto-save

---

## Tips for Better Results

### Writing Better Prompts

**Be specific**: Instead of "help with writing," try "help me write a professional email declining a meeting invitation"

**Give context**: "I'm a beginner at cooking" helps the AI adjust its advice level

**Ask for formats**: Request bullet points, step-by-step instructions, or examples when helpful

**Break down complex requests**: Ask one question at a time for complicated topics

### Managing Costs (Cloud AI)

1. Monitor usage in Settings → Cost Tracking
2. Set spending limits to avoid surprises
3. Use local models for simple tasks, cloud AI for complex ones
4. Choose less expensive models for basic questions

### Keeping Conversations Organized

- Use descriptive names when saving conversations
- Add relevant tags immediately while you remember the context
- Create folders for different projects or topics
- Regularly clean up test conversations and duplicates

---

## Troubleshooting

### App Won't Start
- Restart your computer
- Check if you have enough free disk space
- Try running as administrator (right-click → Run as Administrator)

### Models Keep Crashing
- Close other memory-intensive apps
- Try a smaller AI model
- Increase virtual memory in your system settings
- Check for app updates

### Can't Find Saved Conversations
- Check all folders in Memories, not just Recent
- Try searching with different keywords
- Look in Trash folder for accidentally deleted items
- Check if filters are hiding results

### Getting Error Messages
- Note the exact error message
- Check Settings → System Info for diagnostic information
- Try restarting the app
- Check the help section for your specific error code

---

## Getting Help

### Built-in Help
- Use the Updates tab to see what's new
- Check Settings → System Info for technical details
- Look for error codes in the diagnostic logs

### When to Contact Support
- Persistent crashes or errors
- Features not working as described
- Questions about privacy and security
- Suggestions for improvements

**Remember**: MemoDesk is designed to work offline and keep your data private, so you're in control of your information at all times. Take advantage of the memory system to build your own personal AI knowledge base over time!