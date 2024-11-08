### **Lesson 4: Video and Source**

#### **Objective:**  
Students will learn how to add video content to a webpage, using both a local video file with the `<video>` tag and a YouTube video embed with the `<iframe>` tag.

---

### **Instructions**

#### **Step 1: Open `iframe.html`**
1. Navigate to your `media-gallery` folder and open the `iframe.html` file in your text editor.

#### **Step 2: Add a Section for Videos**
2. Below the existing iframe for `iframe.html`, add a new heading to indicate the start of the video content:
   ```html
   <h2>Video Content</h2>
   ```

#### **Step 3: Embed a Local Video with the `<video>` Tag**
3. Visit [Pexels - Video website](https://www.pexels.com/videos/) and download a video. Make sure to place the video in a folder called `videos` within your `media-gallery` folder. Your file structure should look like this:
```
   media-gallery/
   │   ├── images/
   │   ├── your-image-file.jpg
   │   ├── your-image-file.jpg
   │   └── your-image-file.jpg
   ├── videos/
   │   └── your-video-file.mp4
   ├── iframe.html
   └── index.html
   ```

  - Below the new heading, use the `<video>` tag to add a video that you have saved in the `media-gallery` folder.:
   ```html
   <video width="600" height="400" controls>
       <source src="UPDATE WITH YOU VIDEO FILE NAME" type="video/mp4">
       Your browser does not support the video tag.
   </video>
   ```
   - **Explanation of attributes**:
     - `width="600"` and `height="400"`: Sets the display size of the video.
     - `controls`: Adds play/pause, volume, and fullscreen controls for the video.
     - `<source src="UPDATE WITH YOU VIDEO FILE NAME" type="video/mp4">`: Specifies the video file and format.

4. Add a caption or short description below the video to explain its content:
   ```html
   <p>This is a sample video hosted locally in the media-gallery folder.</p>
   ```

#### **Step 4: Embed a YouTube Video Using `<iframe>`**
5. Below the local video, embed a YouTube video using the `<iframe>` tag. You can use any [YouTube](https://www.youtube.com/) link to copy  the iframe code:


6. Add a caption or description below the YouTube embed to describe the video:
   ```html
   <p>This is an embedded video from YouTube.</p>
   ```

#### **Step 5: Save and Preview**
7. Save `iframe.html` and open it in a web browser to preview the local video and YouTube embed.
8. You should see the both local video and Youtube video added below the iframe.

#### **Step 6: Submit Your Work**
9. Once you've confirmed that the videos looks good, submit the following:
   - Take a screeshot of your `iframe.html` page by holding `CMD+SHIFT+4`, then use your mouse to select the webpage. Add screenshot to the media-gallery folder.
   - The zipped media-gallery folder with the index.html file, iframe.html, screenshot.png, images folder. **DO NOT INCLUDE THE VIDEO FOLDERS.**
      - *The video folder is too large and it will not upload to Google Classroom.*
   - Upload the zip file to the classwork assignment on Google Classroom

### **Outcome**
- Students will have successfully embedded both a locally hosted video using the `<video>` tag and an online video from YouTube using the `<iframe>` tag, expanding their understanding of multimedia integration on a webpage.
