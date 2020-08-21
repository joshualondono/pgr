# Provide - Grant - Recieve 

# PGR allows you to create a contract between a provider(funder) and reciever with a granter(mediator) that must complete contract and release funds to the receiever. Only the reciever 

## How it works 

1. Provider creates a contract by creating a note, hold amount, release date, and by adding proivder, reciever and granter contact information. Keys are sent to all three users. 

~~~~ js

app(note, holdAmount, releaseDate, provider, receiver, granter)

~~~~

2. Granter releases funds or extends project by entering their key on the release date. If nothing is done 30 days after release date, 33% of funds are released to reciever and the rest refunded to provider. 

~~~~ js

app.release(granterKey)

~~~~




