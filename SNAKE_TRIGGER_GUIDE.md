# GitHub Snake Animation - Manual Trigger Guide

## 🐍 Snake Animation is Now Configured!

### Status: Ready to Generate ⏳

Your GitHub Snake animation workflow is properly set up and will generate in the following situations:

---

## ⚡ OPTION 1: Manual Trigger (Fastest - Recommended)

1. **Go to:** https://github.com/Sandept/About-me/actions
2. **Click on:** "Generate Snake" workflow (on the left)
3. **Click:** "Run workflow" button
4. **Select:** "master" branch from dropdown
5. **Click:** "Run workflow" (green button)
6. **Wait:** 1-2 minutes for generation
7. **Refresh:** Your repository README page

✅ **The snake animation will appear immediately after workflow completes!**

---

## ⏰ OPTION 2: Automatic Trigger (Happens Automatically)

The workflow will automatically generate the snake animation:

- ✅ **Daily**: Every day at 00:00 UTC (midnight)
- ✅ **On Every Push**: Any code push to master/main branches
- ✅ **On Every Pull Request**: Every PR to master branch

---

## 📊 How to Monitor Workflow Status

1. Go to: https://github.com/Sandept/About-me/actions
2. Click "Generate Snake" workflow
3. You'll see:
   - ✅ Green checkmark = Successfully generated
   - ⚠️ Yellow dot = Currently running
   - ❌ Red X = Error (rare)

---

## 🔗 Important Links

- **Main Repository:** https://github.com/Sandept/About-me
- **Actions Tab:** https://github.com/Sandept/About-me/actions
- **Output Branch:** https://github.com/Sandept/About-me/tree/output *(created after first run)*
- **Snake SVG (Dark):** https://raw.githubusercontent.com/Sandept/About-me/output/github-snake-dark.svg
- **Snake SVG (Light):** https://raw.githubusercontent.com/Sandept/About-me/output/github-snake.svg

---

## ✅ Workflow Configuration Status

```yaml
✅ Workflow Name: Generate Snake
✅ Schedule: Daily at 00:00 UTC
✅ Triggers: 
   - workflow_dispatch (manual)
   - push (on code push)
   - pull_request (on PR)
   - schedule (daily)
✅ Repository: Sandept/About-me
✅ User: Sandept
✅ Output Branch: output
✅ SVG Files: 2 (dark + light mode)
```

---

## 🐛 Troubleshooting

### Snake Animation Still Not Showing?

1. **Check workflow status:**
   - Go to https://github.com/Sandept/About-me/actions
   - Verify "Generate Snake" workflow ran successfully

2. **Clear browser cache:**
   - Press: Ctrl + Shift + Delete
   - Clear cache from the last day
   - Hard refresh: Ctrl + Shift + R

3. **Manually trigger workflow** (see OPTION 1 above)

4. **Check output branch exists:**
   - Go to: Branch selector dropdown on repo
   - Look for "output" branch

---

## 📝 What Happens When Workflow Runs

1. ⚙️ Ubuntu runner starts
2. 📥 Clones your repository
3. 🐍 Runs Platane/snk@v3 action (generates SVGs)
4. 📤 Pushes SVG files to `output` branch
5. 🔄 GitHub Pages deploys files
6. ✨ Your README displays the animation!

---

## 🎯 Expected Output

When the workflow completes successfully:

```
✅ 2 SVG files created:
   - github-snake.svg (light mode)
   - github-snake-dark.svg (dark mode)

✅ Pushed to: output branch

✅ Available at:
   - https://raw.githubusercontent.com/Sandept/About-me/output/github-snake-dark.svg
   - https://raw.githubusercontent.com/Sandept/About-me/output/github-snake.svg
```

---

## ⏱️ Timeline

- **Now:** Workflow configured and ready
- **Next 1-2 mins:** Trigger workflow manually OR
- **Daily at 00:00 UTC:** Automatic daily generation
- **After 1-2 mins of workflow run:** Snake animation appears in README

---

## ✨ Additional Features

Your snake animation will show:
- 📊 Your GitHub contribution graph
- 🎮 Snake eating commits as food
- 🌙 Dark mode and light mode support
- 🔄 Updates daily automatically
- 🎨 Matches Tokyo Night theme (purple accent color)

---

**Need help?** Check the workflow logs at: https://github.com/Sandept/About-me/actions

---

Generated: April 14, 2026
