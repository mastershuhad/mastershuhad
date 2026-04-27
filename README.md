<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mohamed Shuhad - GitHub README</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            background: linear-gradient(135deg, #0a0a0a 0%, #0D1117 100%);
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', 'Roboto', 'Fira Code', monospace;
            padding: 40px 20px;
            color: #ffffff;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            background: #0D1117;
            border-radius: 20px;
            box-shadow: 0 20px 60px rgba(0,0,0,0.5);
            overflow: hidden;
            position: relative;
        }

        .copy-btn-container {
            position: sticky;
            top: 20px;
            z-index: 1000;
            display: flex;
            justify-content: flex-end;
            padding: 20px 30px;
            background: transparent;
        }

        .copy-btn {
            background: linear-gradient(135deg, #58A6FF, #3b82f6);
            color: white;
            border: none;
            padding: 12px 28px;
            font-size: 16px;
            font-weight: 600;
            border-radius: 50px;
            cursor: pointer;
            font-family: 'Fira Code', monospace;
            transition: all 0.3s ease;
            box-shadow: 0 4px 15px rgba(88, 166, 255, 0.3);
            display: flex;
            align-items: center;
            gap: 10px;
        }

        .copy-btn:hover {
            transform: translateY(-2px);
            box-shadow: 0 6px 20px rgba(88, 166, 255, 0.5);
            background: linear-gradient(135deg, #6cb4ff, #4a90e2);
        }

        .copy-btn:active {
            transform: translateY(0);
        }

        .copy-btn.copied {
            background: linear-gradient(135deg, #10b981, #059669);
            box-shadow: 0 4px 15px rgba(16, 185, 129, 0.3);
        }

        .readme-content {
            padding: 0 20px 20px 20px;
        }

        .toast {
            position: fixed;
            bottom: 30px;
            right: 30px;
            background: #10b981;
            color: white;
            padding: 12px 24px;
            border-radius: 10px;
            font-family: 'Fira Code', monospace;
            font-size: 14px;
            font-weight: 600;
            z-index: 2000;
            animation: slideIn 0.3s ease;
            box-shadow: 0 4px 15px rgba(0,0,0,0.3);
        }

        @keyframes slideIn {
            from {
                transform: translateX(100%);
                opacity: 0;
            }
            to {
                transform: translateX(0);
                opacity: 1;
            }
        }

        /* GitHub Markdown Styles */
        .markdown-body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', 'Noto Sans', Helvetica, Arial, sans-serif;
            line-height: 1.6;
        }

        .markdown-body h1, .markdown-body h2, .markdown-body h3 {
            border-bottom: 1px solid #21262d;
            padding-bottom: 0.3em;
        }

        .markdown-body code {
            background: #161b22;
            padding: 0.2em 0.4em;
            border-radius: 6px;
            font-family: 'SF Mono', 'Fira Code', monospace;
        }

        img {
            max-width: 100%;
            height: auto;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="copy-btn-container">
            <button class="copy-btn" id="copyBtn">
                📋 Copy README.md
            </button>
        </div>
        <div class="readme-content" id="readmeContent">
            <div align="center">

<!-- Top Wave -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:FF6B6B,25:FF8E53,50:FFC75F,75:6BCB77,100:4D96FF&height=160&section=header&text=Mohamed%20Shuhad&fontSize=42&fontColor=ffffff&fontAlignY=38&animation=fadeIn&desc=Software%20%7C%20Web%20%7C%20App%20Developer&descAlignY=58&descSize=18" alt="header wave"/>

<!-- Typing Animation (subtitle) -->
<img width="100%" src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=22&pause=1000&color=58A6FF&center=true&vCenter=true&width=900&height=50&lines=Aspiring+Software+Developer+%F0%9F%92%BB;Web+%26+App+Developer+%F0%9F%9A%80;React+%26+Next.js+Enthusiast+%E2%9A%9B%EF%B8%8F;Kotlin+%26+Python+Programmer+%F0%9F%90%8D;Always+Learning%2C+Always+Building+%F0%9F%8C%B1" alt="Typing SVG" />

<br/>

<!-- Profile Views & Followers Badges -->
![Profile Views](https://komarev.com/ghpvc/?username=mastershuhad&color=58A6FF&style=for-the-badge&label=PROFILE+VIEWS)
[![GitHub followers](https://img.shields.io/github/followers/mastershuhad?style=for-the-badge&color=58A6FF&labelColor=1a1a2e)](https://github.com/mastershuhad)

</div>

---

## 🧑‍💻 About Me

```kotlin
data class Developer(
    val name: String     = "Mohamed Shuhad",
    val role: List<String> = listOf(
        "Software Developer",
        "Web Developer",
        "App Developer"
    ),
    val education: String = "Undergraduate Student @ University of Kelaniya",
    val location: String  = "Sri Lanka 🇱🇰",
    val currentFocus: List<String> = listOf(
        "Mastering JavaScript & React",
        "Building with Next.js",
        "Android App Dev with Kotlin",
        "Problem Solving with Python"
    ),
    val goal: String = "Become a skilled Software & Web Developer 🎯",
    val funFact: String  = "I learn best by building real projects 🔨"
)
