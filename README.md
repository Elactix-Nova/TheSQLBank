# TheSQLBank
## What it does
TheSQLBank is a simple terminal interface that emulates online banking. It uses CockroachCloud's Online Database to store accounts and their details. Apart from simple actions like depositing/withdrawing it can also be used to take out loans, file insurance etc.
## How we built it
TheSQLBank is built upon python and uses CockroachDB's database along with psycopg2 module for connecting to the database and editing it.
## Challenges we ran into
The major challenge we ran into was our inexperience with CockroachDB. Our familiarity with SQL queries made it easier to build the app but the setup process was long and difficult including the authentication of our devices using a CA certificate which finally got downloaded after a lot of changes and tweaks.
## Accomplishments that we're proud of
We are proud of the fact that we are finally able to use CockroachDB not only for cloud databases but also for local hosting and also having learnt how to create authentication certificates for root users as well as clients.
## What's next for TheSQLBank
The next step for TheSQLBank would be to develop a backend to enable users to login with social credentials like emails. Apart from this we would also like to enable a peer-to-peer lending service which enables users to lend credit at a fixed interest rate to other users.
