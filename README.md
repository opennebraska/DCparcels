# DCparcels

Douglas County Nebraska parcel search

The County already has a parcel search tool: http://douglascone.wgxtreme.com/

It's very cool -- you can type in addresses and get the parcel information and an interactive
map where you can click on neighboring parcels and see all the information about those nearby
parcels too.

What it doesn't offer that we want:

1. The address search is very finnicky:
```
    1214 N 34 St       works
    1214 North 34 St   no results
    1214 N 34th St     no results
    1214 N 34 Street   no results
```
We can solve that from a human UI perspective via Elasticsearch listing valid inputs?

2. For any given parcel, the ownership information is displayed. But nowhere (we've found)
   can you find the other parcels that owner also owns.

In the event that you're a renter unhappy with your landlord it's currently difficult 
(tricky) to find the owner information for where you live, and when you do you don't
know what other parcels that owner also owns. Having that information might be helpful
for collaborating communication with the owner.

Further work might include linking to https://opencorporates.com.
