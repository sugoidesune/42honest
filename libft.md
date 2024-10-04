Frequent Reasons to fail the project:

| Reason                                                                                                      | Failcount |
| ----------------------------------------------------------------------------------------------------------- | --------- |
| Calloc - when nmemb or size is 0, the function returned NULL instead of malloc(0) (do not trust the manual) | 1         |
| Calloc - should protect against int over flow when multiplying nmemb and size                               | 1         |
