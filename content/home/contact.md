+++
# Contact widget.
widget = "contact"
active = true
date = "2016-04-20T00:00:00"

title = "Contact Me"
subtitle = ""

# Order that this section will appear in.
weight = 70

# Automatically link email and phone?
autolink = false

+++

<form name="contact" netlify>
  <p>
    <label>Your Name: <input type="text" name="name"></label>   
  </p>
  <p>
    <label>Your Email: <input type="email" name="email"></label>
  </p>
  <p>
    <label>Message: <textarea name="message"></textarea></label>
  </p>
  <p>
    <button type="submit">Send</button>
  </p>
</form>

