Spring Boot @Controller
@Controller annotation indicates that the annotated class is a controller. 
It is a specialization of @Component and is autodetected through classpath scanning. 
It is typically used in combination with annotated handler methods based on the @RequestMapping annotation. 
@RestController is a sibling convenience annotation for creating Restful controllers.

Request Mapping
The @RequestMapping annotation is used to define the Request URI to access the REST Endpoints. 
We can define Request method to consume and produce object. The default request method is GET.