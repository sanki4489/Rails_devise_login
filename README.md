Devise gem usuage:-
1.Sign Up User
i)hashed password
ii)confirmation
iii)forgot password
2.Log In User
i)remember me
3.Log Out User

Devise gem setup:-
1.Install gem-> gem 'devise'
2.bundle install
3.rails generate devise:install
4.rails generate devise User
5.rails db:migrate
6.before_action :authenticate_user!
7.Set the flash messages

Devise bootstrap view gem 1.<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css" integrity="sha384-MCw98/SFnGE8fJT3GXwEOngsV7Zt27NXFoaoApmYm81iuXoPkFOJwJ8ERdknLPMO" crossorigin="anonymous">
2.gem 'devise-bootstrap-views', '~> 1.0'
3.bundle install
