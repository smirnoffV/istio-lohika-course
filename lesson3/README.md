# istio-lohika-course

## Lesson #3

* Kiali UI video 10% traffic to v2 and 90% traffic to v1
![canary_dashboard](screenshots/canary.gif?raw=true)
* See [Virtual Service](k8s/traffic-routing/dev-environment/frontend-vs.yml) for frontend for checking task #2 
(traffic routing by provided header)
* Load balancing and circuit breaking for [author](k8s/traffic-routing/lb-an-cb/author-dr.yml) and [book](k8s/traffic-routing/lb-an-cb/book-dr.yml) services.