# Contribution Guidelines

Please ensure your pull request adheres to the following guidelines:

- Search previous suggestions before making a new one, as yours may be a duplicate.
- Make an individual pull request for each suggestion.
- Additions should be added to the bottom of the relevant category.
- Use the following format: 
  
  ```markdown
  ### Title of screensaver

  > Short description of screensaver.

  Price (if applicable)

  [![](screenshots/filename.png)](http://url/to/screensaver)
  ```
  
- New categories, or improvements to the existing categorization are welcome.
- Keep descriptions short and simple, but descriptive.
- Start the description with a capital and end with a full stop/period.
- Check your spelling and grammar.
- Make sure your text editor is set to remove trailing whitespace.
- The pull request should have a useful title and include a link to the App and why it should be included.

## How to Get Screenshots

Capture a screenshot with this command. You can change the 5 to adjust the number of seconds it waits to take the screenshot.

```
sleep 5; screencapture -m ~/Desktop/screenshots/image.png
```

Resize the image with this command. This will resize all png images in the screenshots directory.

```
sips -Z 1000 ~/Desktop/screenshots/*.png
```

---

Thank you for your suggestions!
