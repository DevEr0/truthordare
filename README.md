# Afterglow — Truth or Dare ♡

A romantic, mobile-friendly, jelly-inspired question game with **100 prompts** (80 truths and 20 dares).

## Publish on GitHub Pages

1. Create a new public GitHub repository.
2. Upload **`dist/index.html`** to the **root** of the repository as **`index.html`** (not inside a `dist` folder).
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, then select **`main`** and **`/(root)`**. Save.
5. GitHub will show your website URL after the deployment finishes.

If you downloaded the ZIP, simply take the `index.html` file from it and upload that to the repository root.

No dependencies, build command, API keys, or hosting account beyond GitHub are needed. The page works as a single HTML file.

## Editing questions

Click **Edit questions** at the top of the website.

- **This question:** Replace the prompt currently displayed. Click **Save this question**.
- **Bulk paste:** Choose a category, paste one question per line (optionally numbered), then click **Apply pasted questions**.
- **All 100 questions:** Choose the last option and paste exactly 100 lines, ordered Sweet (1–20), Spicy (21–40), Funny (41–60), Group (61–80), Dares (81–100).
- **Download HTML:** Get an updated standalone `index.html` file containing your changes.

Browser edits are saved only **on that device and in that browser**. To publish the edits for everyone, download the updated `index.html` and replace the file in your GitHub repository. GitHub Pages will redeploy it.

The site also supports shuffle, sequential mode, previous question, searching all questions, copying a question, and keyboard left/right navigation.

## Customizing the design

Open `index.html` in a text editor. All color and layout styles are in the `<style>` block near the top; the original questions are in `<script id="question-data" type="application/json">` near the bottom. The page is self-contained, with no external image or font requests.
