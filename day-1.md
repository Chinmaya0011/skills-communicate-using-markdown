# Daily Learning

## Morning Planning
- [ ] Check out the [github blog](https://github.blog/) for topic ideas.
- [ ] Learn about [GitHub Pages](https://skills.github.com/#first-day-on-github).
- [ ] Convert my first blog post into an actual webpage.

## Review

Convert an image or video from dark mode to light mode using [ffmpeg](https://www.ffmpeg.org):

```bash
ffmpeg -i input.mp4 -vf "negate,hue=h=180,eq=contrast=1.2:saturation=1.1" output.mp4


---

### 🔹 Steps to complete:
1. Open your repo → switch to **`start-blog` branch**.  
2. Edit **`day-1.md`**, replace all content with the above.  
3. Click **Preview** → you should see:  
   - A heading `Daily Learning`  
   - A task list under `Morning Planning` with ✅ checkboxes  
   - A **bash code block** under `Review`.  
4. Commit changes → directly to `start-blog`.  

---

👉 After this, Mona bot should mark Step 3 ✅ and unlock **Step 4 (Add an image)**.  

Do you want me to also give you the **Step 4 file (with image included)** right away so you can paste and move faster?
