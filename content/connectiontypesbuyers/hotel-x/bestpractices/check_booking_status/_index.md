+++
title = "Check Booking status"
pagetitle = "Check Booking status"
description = ""
icon = "fa-exchange"
weight = 3
alwaysopen = false
isDirectory=false
+++

It is the Buyer´s responsability to check the status of the booking. Getting an error in the response (without a status being displayed) is not meaning the booking hasn't been confirmed as well as getting a response without errors in Book query, it is not meaning that the booking has been confirmed. It is strictly required for an effective use of the API. 

There are 4 different status for the response of Book query:

1. **OK**:The reservation was completed with no problems.
2. **ON_REQUEST**: The reservation was completed but the product is still not available, so the reservation goes into a waiting list. It is the client’s responsibility to check if the booking is OK.
3. **UNKNOWN**: The reservation process through TGX was completed but due to a supplier error or a timeout, the reservation status is unknown. It is the client’s responsibility to check if the booking is OK. 
4. **PENDING_COMMIT**: The payment has been confirmed in provider's side, but is necessary make a commit in order to confirm the reservation. 
