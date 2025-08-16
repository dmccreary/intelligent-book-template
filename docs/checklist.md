# Checklist for Site Customization

This book is designed to be quickly customized to meet the needs of your school.
Use this checklist to do the customization work.

1. Customize the fields in your mkdocs.yml file including the URLs and site description.  This is where you can change the colors and logos of your microsite
2. Configure Google Analytics to use the right site ID - you will need your own Google account to do this
3. Make sure that your .gitignore file includes the ```site``` directory
3. Test the build using `mkdocs build` and verify there are no errors
4. Make sure the Edit button appears in each page
5. Make sure that code color heightening renders correctly
6. run ```git config advice.addIgnoredFile false``` to ignore warning messages.  This is important if you do `git add *` to add all changes