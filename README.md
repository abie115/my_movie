README

Projekt na zaliczenie Architektura Serwisów Komputerowych
*Ruby version: 2.2.1
*Ruby on Rails version: 4.2.1
*Dodatkowe gemy:<br>
gem 'sass-rails', '>= 5.0.2'<br>
gem 'bootstrap-sass', '~> 3.3.4'<br>
gem 'will_paginate',           '3.0.7'<br>
gem 'bootstrap-will_paginate', '0.0.10'<br>
<br><br>
*Deployment instruction:
bundle install --without production
rake db:migrate
rake db:seed

*Dodatkowe uwagii:
Nie można dodawać recenzji filmów, które mają swoją premiere w przyszłosci<br>
Aby móc dodawac, edytować recenzje filmów należy się zalogować<br>



