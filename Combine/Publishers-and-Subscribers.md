# Publishers
*A publisher emits two kinds of events:*
+ Values, also referred to as elemets.
+ A completion event.
  
A publisher can emit zero or more values but only one completion event.Completion event can be normal completion or an error.
***Once a publisher emits a completion event => it finished and can no longer emit any more events***
# Subscribers
# Cancellable