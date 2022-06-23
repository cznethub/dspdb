# dspdb
CZNetHub Data Submission Portal Database

1. Create a .env file containing at least the following:
   1. DATABASE_USERNAME=[database user name here]
   1. DATABASE_PASSWORD=[database password here]
   1. DATABASE_NAME=[name of dsp datanase here]
   1. DATABASE_PORT=[port number serving the database here]
   1. DATABASE_HOST=[DNS name serving the database here]
1. Open the DATABASE_PORT on the DATABASE_HOST's firewall to the subnets making connections.
1. `docker-compose --env-file .env up -d`
