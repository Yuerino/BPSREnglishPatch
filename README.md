 # 🌟 English Patch Installation Guide for Star Resonanse
---

## 📝 How to Install

### 1. **Reset Language Setting**

Before applying the patch, you need to make sure the game language is set to Chinese.

You can do this in one of **two ways**:

**Option A: Delete Save Files**  
Delete the following two files to reset the game's saved language setting:

```
%appdata%\..\LocalLow\bokura\Star\localsave\localsave.bytes  
%appdata%\..\LocalLow\bokura\Star\localsave\localbacksave.bytes
```

**Option B: Change Language to Chinese In-Game**  
In the game setting if you know how

---

### 2. **Install the English Patch**

1. Download the `1494144761.bytes` patch file.  
2. Copy it into your game’s install directory under:

```
STAR RESONANSE(2001991)\Star_Data\StreamingAssets\container\Patch\
```

> ⚠️ **You may repeat this step each time the game updates**, as the file may be replaced.

> 🔄 **Wait for an updated patch file** after each new game update. You can check the GitHub commit history to see if the English patch has been updated before replacing it.

---

### 3. **Switching Back to Chinese**

To revert the game to its original Chinese language, just **delete** the patched file:

```
1494144761.bytes
```

---

## ✅ That’s it!

If the game still shows Chinese text, make sure the patch file is in the right folder and your language is set to Chinese.

---

## 🛠️ Reporting Issues with Broken or Untranslated Text

If you find any broken or untranslated text and want it fixed:

1. **Create an issue** in this GitHub repository.
2. Include:
   - A screenshot showing the broken or incorrect text **in English setting**.
   - A screenshot of the **same screen in Chinese setting**.
   - If possible, OCR and paste the **Chinese text** directly (to speed up the fix).

> 📝 This helps me quickly identify and resolve issues. Thank you for contributing!

---

## ❓ Q&A

### What is `1494144761.bytes` file?

It is the **English translation text file** for the game. This file contains the translated text and is loaded by the game.

### Can I be banned for using this?

It is **unlikely** that you will be reported or banned because of this method, as you do **not modify any official game files**. You only add a translation file that the game is already set up to read.

However, **use it at your own risk**. I am not responsible for any issues that may occur as a result of using this patch.

