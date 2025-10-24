cd path/to/your-portfolio
git init
git add .
git commit -m "Initial portfolio"
# create a GitHub repo and then
git remote add origin https://github.com/<your-username>/<repo>.git
git branch -M main
git push -u origin main<form id="contact-form" name="contact" method="POST" data-netlify="true" netlify-honeypot="bot-field">
  <input type="hidden" name="form-name" value="contact" />
  <input type="hidden" name="bot-field" />
  
  <div style="display:flex;gap:8px">
    <div style="flex:1">
      <label for="name">Name</label>
      <input id="name" name="name" required />
    </div>
    <div style="width:160px">
      <label for="phone">Phone</label>
      <input id="phone" name="phone" />
    </div>
  </div>

  <div style="margin-top:10px">
    <label for="email">Email</label>
    <input id="email" name="email" type="email" required />
  </div>

  <div style="margin-top:10px">
    <label for="message">Message</label>
    <textarea id="message" name="message" rows="5" required></textarea>
  </div>

  <div style="margin-top:10px;display:flex;gap:8px;align-items:center">
    <button class="btn btn-primary" type="submit">Send message</button>
    <div id="form-status" style="color:var(--muted);font-size:14px"></div>
  </div>
</form>
