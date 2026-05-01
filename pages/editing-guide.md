---
layout: default
title: Editing & Updating This Site
---

# 🛠️ Editing & Updating This Site

Welcome! This guide shows you how to edit and update this GitHub Pages site, even if you've never used GitHub before.

---

## 🎯 Why Update This Site?

Anyone can help keep our alliance information fresh and accurate!

- 📝 Fix typos or unclear wording
- 📅 Update event schedules
- ✏️ Add new guides and tips
- 📸 Add community content
- 🔄 Improve existing pages
- 💡 Share your knowledge

**No coding experience required!** We'll use GitHub's web editor.

---

## 🌐 What is GitHub?

GitHub is a platform for storing and collaborating on files (especially code, but also documents).

**Our Setup:**
- 📁 Repository = Folder containing all our alliance documents
- 📄 Files = Individual pages (like this one!)
- 🔄 Changes = When someone edits a file
- ✅ Approval = Updates go live after review

---

## 🚀 Getting Started

### Step 1: Visit the Repository

Go to: **https://github.com/boblzsurvivor-wq/Alliance-Information**

This is where all our files live. You'll see:
- 📄 Files and folders listed
- 📝 README.md (main page)
- 📂 `pages/` folder (contains our alliance pages)

### Step 2: Look at the File You Want to Edit

Files are organized like this:
```
Alliance-Information/
├── index.md                (Homepage)
├── README.md              (Repository home page)
└── pages/
    ├── charter.md         (Alliance Charter)
    ├── structure.md       (Alliance Structure)
    ├── members.md         (Member Information)
    ├── guides.md          (Guides & Resources)
    └── editing-guide.md   (This file!)
```

Click on the file you want to edit.

---

## ✏️ Method 1: Edit in Browser (EASIEST)

This is the simplest way to make changes!

### Step 1: Open the File
1. Go to the repository: https://github.com/boblzsurvivor-wq/Alliance-Information
2. Navigate to the file you want to edit (e.g., `pages/members.md`)
3. Click on the file name to open it

### Step 2: Click the Edit Button
You'll see the file displayed. Look for a **pencil icon ✏️** in the top right.

Click it! This opens the editor.

### Step 3: Make Your Changes
You'll now see the file in an editable text box.

**Make your changes:**
- 🔤 Edit text directly
- ⌫ Delete text you don't want
- ⌨️ Type new content
- ⏮️ Undo with Ctrl+Z (or Cmd+Z on Mac)

### Step 4: Preview Your Changes
Click the **"Preview"** tab to see how your changes look!

Use the **"Edit"** tab to go back to editing.

### Step 5: Save Your Changes
Scroll down to the bottom. You'll see a **"Commit changes"** section.

1. **Commit message**: Write a short description of what you changed
   - Example: "Fix typo in member requirements"
   - Example: "Add new event guide"
   - Example: "Update contact information"

2. **Extended description** (optional): Longer explanation if needed

3. Click **"Commit changes"**

### Step 6: Create a Pull Request
GitHub will show you what changed and ask if you want to create a **Pull Request**.

A Pull Request (PR) is how you propose changes for review:

1. Click **"Create Pull Request"** (if it appears)
2. Add a title and description of your changes
3. Click **"Create Pull Request"**

**Done!** Your changes are now pending review.

### Step 7: Wait for Approval
An officer or maintainer will:
- 👀 Review your changes
- ✅ Approve if looks good
- 💬 Ask questions if needed
- 🔀 Merge (approve) the changes
- 🌐 Your changes go live!

---

## 📝 Markdown Formatting Basics

Our files use **Markdown**, a simple text format. Here's how to format text:

### Headings
```markdown
# Main Heading (H1)
## Subheading (H2)
### Sub-subheading (H3)
#### Level 4 Heading
```

### Text Formatting
```markdown
**bold text**          → renders as bold
*italic text*         → renders as italic
***bold italic***     → renders as bold italic
~~strikethrough~~     → renders with strikethrough
`code snippet`        → renders as code
```

### Lists

**Bullet List:**
```markdown
- Item 1
- Item 2
  - Nested item 2a
  - Nested item 2b
- Item 3
```

**Numbered List:**
```markdown
1. First item
2. Second item
3. Third item
```

### Links
```markdown
[Link text](https://example.com)         → external link
[Internal page](../index.md)              → link to another page
```

### Images
```markdown
![Alt text](image-url)
```

### Tables
```markdown
| Header 1 | Header 2 |
|----------|----------|
| Cell 1   | Cell 2   |
| Cell 3   | Cell 4   |
```

### Line Break
```markdown
---    → creates a horizontal line
```

### Code Block
```markdown
```language
code goes here
```
```

### Blockquotes
```markdown
> This is a quote
> It can span multiple lines
```

### Emojis
```markdown
🎮 🎯 ✅ ❌ 📝 📖 🔗 💬
```

---

## 📖 Editing Examples

### Example 1: Fix a Typo

**Original text:**
```markdown
Our aliance is commited to teamwork.
```

**How to fix:**
1. Find the line with the typo
2. Change "aliance" to "alliance"
3. Change "commited" to "committed"

**Result:**
```markdown
Our alliance is committed to teamwork.
```

### Example 2: Add a New Tip

**Original:**
```markdown
### Combat Tips
- Use cover effectively
```

**New version:**
```markdown
### Combat Tips
- Use cover effectively
- Communicate with teammates
- Manage your ammo carefully
```

### Example 3: Update an Event Schedule

**Original:**
```markdown
**Next Raid**: Friday at 7 PM EST
```

**Updated:**
```markdown
**Upcoming Raids**:
- Friday at 7 PM EST (Beginner)
- Saturday at 2 PM EST (Intermediate)
- Sunday at 5 PM EST (Advanced)
```

### Example 4: Add a New Section

**Original:**
```markdown
## Contact Info
Contact our officers in-game.
```

**Enhanced:**
```markdown
## Contact Info

### In-Game
- Message any officer in alliance chat
- Response typically within 24 hours

### Emergency Issues
- Contact Alliance Leader directly
- For urgent matters affecting multiple members

### Questions?
- Check the [FAQ](guides.md#faq)
- Ask in alliance chat for quick answers
```

---

## 🆘 Troubleshooting

### Problem: "I can't find the edit button"

**Solution:**
- Make sure you're logged into GitHub
- The pencil ✏️ icon should be in the top right
- If you don't see it, you may need to click "View" tab first

### Problem: "My changes disappeared"

**Solution:**
- If you didn't click "Commit changes", they weren't saved
- Always look for the commit button at the bottom
- You'll see a confirmation message after committing

### Problem: "I made a mistake in my commit"

**Solution:**
- **Before approved**: Create another PR with the fix
- **After approved**: Make a new edit correcting the issue
- No big deal—mistakes are fixable!

### Problem: "The preview looks weird"

**Solution:**
- Check markdown syntax (missing symbols?)
- Make sure headings have `#` symbols
- Verify links use `[text](url)` format
- Look for unclosed brackets or parentheses

### Problem: "Can't see my changes on the website"

**Solution:**
- Your PR must be **merged** (approved) first
- Check status of your PR on GitHub
- After merge, website updates within 5 minutes
- Clear your browser cache if still not showing

---

## 🎯 Best Practices for Editing

### DO:
✅ Make changes one topic at a time  
✅ Write clear commit messages  
✅ Preview changes before committing  
✅ Fix typos and grammar  
✅ Add helpful examples  
✅ Keep formatting consistent  
✅ Link to related pages  
✅ Test links to make sure they work  

### DON'T:
❌ Make huge changes all at once  
❌ Use unclear commit messages  
❌ Change formatting inconsistently  
❌ Remove important information  
❌ Break existing links  
❌ Edit files you're unsure about  
❌ Commit without previewing  
❌ Overwrite others' recent changes  

---

## 📋 Common Edits by Role

### If You're a Regular Member:
- ✅ Fix typos
- ✅ Improve clarity
- ✅ Add tips and strategies
- ✅ Share helpful info
- ⚠️ Check with officers before major changes

### If You're an Officer:
- ✅ Update schedules and events
- ✅ Modify policies if approved
- ✅ Add important announcements
- ✅ Manage member records
- ✅ Approve/reject member PRs

### If You're the Alliance Leader:
- ✅ All of the above
- ✅ Make governance decisions
- ✅ Approve major changes
- ✅ Manage repository settings

---

## 🔍 How to Review Changes

**Officers should do this when reviewing PRs:**

1. **Click on the Pull Request** - See what changed
2. **Check "Files Changed" tab** - Review edits
3. **Look at the diff** - Green = added, Red = removed
4. **Verify accuracy** - Is the info correct?
5. **Check formatting** - Does it look good?
6. **Comment if needed** - Ask questions
7. **Approve & Merge** - If everything looks good!

---

## 📚 Additional Resources

### Learn More About GitHub
- 📖 [GitHub Markdown Guide](https://guides.github.com/features/mastering-markdown/)
- 📖 [GitHub Docs](https://docs.github.com/en)
- 🎥 [YouTube: GitHub for Beginners](https://www.youtube.com/results?search_query=github+for+beginners)

### Learn More About Markdown
- 📖 [Markdown Guide](https://www.markdownguide.org/)
- 📖 [CommonMark Spec](https://spec.commonmark.org/)

### Our Repository
- 🏠 [Alliance Information Repo](https://github.com/boblzsurvivor-wq/Alliance-Information)
- 📖 [Main README](../README.md)
- 🌐 [Live Website](https://boblzsurvivor-wq.github.io/Alliance-Information/)

---

## 💡 Tips & Tricks

### Tip 1: Use Preview Tab Frequently
Always check your changes before committing! The preview shows exactly how it'll look.

### Tip 2: Keep Commit Messages Clear
"Fixed typo" is clear. "Updated" is vague. "Fixed typo: 'aliance' → 'alliance' in members.md" is excellent!

### Tip 3: Link Between Pages
Use relative links to connect pages:
- `[link](../index.md)` - Go up one folder to index.md
- `[link](charter.md)` - Link to file in same folder
- `[link](#section)` - Link to section within same page

### Tip 4: Copy Formatting from Existing Pages
When adding new content, copy the formatting style from existing similar sections.

### Tip 5: Test Your Links
After editing, click the links you added to make sure they work!

### Tip 6: Keep It Simple
Don't overcomplicate formatting. Bold, italics, lists, and headers usually suffice.

---

## 🎉 Your First Edit: Practice

Want to try your first edit? Here's a safe practice:

1. Go to the **Guides & Resources** page (`pages/guides.md`)
2. Click the edit button (pencil ✏️)
3. Scroll to the end before the "Related Pages" section
4. Add a new tip like:
   ```markdown
   ### My Alliance Tip
   [Write a helpful gaming tip here!]
   ```
5. Preview it
6. Commit with message: "Add community tip: [your tip title]"
7. Create a Pull Request
8. Done! Wait for approval.

This is a low-risk way to practice!

---

## 🤝 Getting Help

**Questions about editing?**

- 💬 Ask in alliance chat!
- 📧 Message an officer
- 📝 Create an issue in the [repository](https://github.com/boblzsurvivor-wq/Alliance-Information/issues)
- 📖 Re-read this guide (might have the answer!)

---

## 🎯 Quick Command Reference

| What You Want | What to Use |
|---------------|-----------|
| Make text **bold** | `**text**` |
| Make text *italic* | `*text*` |
| Create a heading | `# Heading` |
| Create a link | `[text](url)` |
| Create a list | `- item` |
| Create a code block | ` ```code``` ` |
| Create a table | Use `\|` separators |
| Add a line | `---` |

---

## 🔗 Related Pages

- **[Home](../index.md)** - Back to homepage
- **[Guides & Resources](guides.md)** - Gameplay guides and tips
- **[Alliance Charter](charter.md)** - Our mission and values
- **[GitHub Repository](https://github.com/boblzsurvivor-wq/Alliance-Information)** - Source files

---

**Last Updated**: 2026-05-01

🛠️ *You're now ready to contribute to our alliance information hub!*
