# Rails : Controller - View

Terminal:
```bash
cd ~/Desktop/coding_skills/
```

Terminal:
```bash
rails new --database postgresql akinator
```

Terminal:
```bash
cd akinator
```

Terminal:
```bash
rails s
```

Open browser at http://localhost:3000/

Open sublime text

Terminal:
```bash
rails generate controller Pages home
```

Sublime text: /config/routes.rb
```ruby
  # get 'pages/home'
  root to: 'pages#home'
```

Sublime text: /views/pages/home.html.erb
```html
<h1>Akinator</h1>
<p>Challenge me to see if I can find who you think!</p>
```