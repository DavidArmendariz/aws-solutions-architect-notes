# Geoproximity routing policy

* Route traffic to your resources based on the geographic location of users and resources
* Ability to shift more traffic to resources based on the defined bias
* To change the size of the geographic region, specify bias values:
  * To expand (1 to 99) - more traffic to the resource
  * To shrink (-1 to -99) - less traffic to the resource
* Resources can be:
  * AWS resources (specify AWS region)
  * Non-AWS resources (specify latitude and longitude)
* You must use Route 53 Traffic Flow to use this feature
