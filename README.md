<h1>introduction</h1>

<b>SiminBooks</b> is a an organization which believes in <b>public lecture</b> (also know as open lecture). in order to accomplish this goal, SiminBooks is raising money in order to buy and deliver books for people who are very poor.
SiminBooks development team has decided to use blockchain trusted transaction networks in order to make donators assure that, their money has been put in a good use.

As SiminBooks's development team decided, Hyperledger Fabric network has been implemented on a Ubuntu(18.04) server.
in order to run the network, we had to install some prerequisites, whitch they are listed below:
1.cURL
2.Docker and Docker Compose
3.Javascript programming language
4.Go language
5.Node.JS

once we were ready, we installed the Fabric Samples and binaries using the command below to pull down the binaries and images.
curl -sSL https://bit.ly/2ysbOFE | bash -s

as we made it through we brought up our first network using the command below
./network.sh up
