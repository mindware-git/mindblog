# Blogger Posting Guideline  
This document defines how the automated blogging system works for both Naver Blog and Google Blogger.  
It acts as the design manual and operating rulebook.

## 1. Purpose (Why)
The goal of this system is to **automatically generate high‑quality news summary posts** for my blogs (“Mindware Insight”), optimized for:
- **Naver Blog SEO**
- **Google Blogger global SEO**
- Consistent, professional formatting
- Easy automation (scheduled or triggered posting)

## 2. Input Source (What)
The system receives **one or more URLs** to recent news articles from User

**If the user does not provide any URL**, the system must ask the user to supply at least one news article URL before generating an article.

## 3. Processing Steps
1. **Scrape article**  
   - Extract main text  
   - Remove ads, irrelevant content  

2. **Identify core points**  
   - Summaries limited to 3–5 bullets  
   - Focus on facts  

3. **AI Rewrite**  
   - Clear, concise tone  
   - Neutral but informative  

4. **Insight Generation**  
   - Short expert‑style interpretation  
   - Business or tech perspective  

5. **Language Conversion**  
   - Korean → Naver  
   - English → Blogger  

6. **Final Formatting**  
   - Apply templates  
   - Add hashtags  
   - Add title formatting  

## 4. Categories
The blog should automatically categorize posts into:
- **News**  
- **Tech**  
- **AI**  
(Expand later if needed)

## 5. Template

### Long‑Form Blog Style Requirement  
All generated articles must follow a **long‑form narrative blog style**, not a short summary.  
- No bullet‑style "Key Summary" sections  
- The article must read like a natural blog post with smooth paragraphs  
- Include background context, explanation, and commentary as needed  
- Minimum length: 5–7 paragraphs unless the source content is extremely short  

### Image Requirement  
Each article **must include at least one image**, using the following markdown format:

```
![IMAGE_DESCRIPTION](IMAGE_URL_OR_PLACEHOLDER)
```

If the source URL does not contain an image, include a placeholder such as:

```
![Related Image](https://via.placeholder.com/800x450)
```

See `NEWS.md` for specific article template usage.
Make new article with file name {DATE}_{TITLE-WITH-DASHES}.md  
(TITLE must use hyphens `-` instead of underscores `_`, similar to URL slugs)
