web: npm install --prefix client && npm run build --prefix client && cp -a client/build/. public/ && rake db:migrate && rails server -b 0.0.0.0 -p ${PORT:-3000}