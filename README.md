# Tailwind CSS Content Configuration Bug

This repository demonstrates a common issue when using Tailwind CSS: styles not being picked up due to an incorrectly configured `content` option in the `tailwind.config.js` file.

**Problem:** The Tailwind CSS configuration doesn't properly scan the source files for custom styles.  This can lead to unexpected behavior where styles aren't applied, despite correct class usage in components.

**Solution:** Carefully specify the directories and file extensions containing your components in the `content` array within your `tailwind.config.js` file.

This repository illustrates the bug and provides a corrected solution.