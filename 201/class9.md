# Class 9 Notes

### **Forms

**Why Forms**
- Forms allow users to search
- Allows users to perform other functions online used when signing up as a member for something, online shopping, newsletters or mailing lists.


## Types of Form controls**
There are several use cases for forms on you site.
- Adding Text
- Making Choices
- Submitting Forms
- Uploading Files
- Subscribing


## How forms work

1. User fills out the form
2. The name of each form control is sent to the server along with the value the user enters or selects
3. The server processes the information using a programming language such as PHP, C#, VB.net, or Javait may also store the informationin a database.
4. The server creates a new page to send back to the browser based on the information received.


Form Structure
```html
<form action="url"method="get">
  <p>This is where the controls will appear</p>
</form>
```

Input Structure
```html
<form action="url">
  <p>Username:
    <input type="Text" name="username" size="15" maxlength="30" />
  </p>
</form>
```

