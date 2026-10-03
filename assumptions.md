# Assumptions

1. The renter enters payment details with contact info. The Payment Service charges the renter only after staff approval.
2. The Website starts the payment action ("Request payment").
3. The sequence diagram starts at submission, so it starts with "submit request" step and only the [available] case.
4. The Website creates the request before sending it to staff.
5. The Email Service sends emails directly to the renter.
6. The renter must submit a new request upon a rejection or payment failure.
7. "Stop search" is a fourth end and new point, used when the renter stops after [not available].
