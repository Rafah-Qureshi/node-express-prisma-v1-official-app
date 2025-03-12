web: npm start
web: npm run prisma:format
web: prisma migrate dev --name added_job_title
web: npm run prisma:seed

release: npx prisma migrate deploy
