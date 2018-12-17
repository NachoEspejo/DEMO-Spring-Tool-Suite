# DEMO-Spring-Tool-Suite

![STS](https://github.com/NachoEspejo/DEMO-Spring-Tool-Suite/blob/master/STS-IMG-Github/spring_tool_suite.png)


## Herramienta usada:
* Spring Tool Suite 3

## Tutorial:

### Crear Spring Starter Project
* Hacemos **_click derecho_**, nos dirigimos a **_New_**, **_Spring Starter Project_**.

![Crear SSP](https://github.com/NachoEspejo/DEMO-Spring-Tool-Suite/blob/master/STS-IMG-Github/Screenshot%20(2).png)


* Rellenamos los campos, con los nombre que veamos convenientes.

![Rellenar campos](https://github.com/NachoEspejo/DEMO-Spring-Tool-Suite/blob/master/STS-IMG-Github/Screenshot%20(3).png)


* Para las dependencias tenemos que seleccionar, **_Web_** y **_Actuator_**.

![Web](https://github.com/NachoEspejo/DEMO-Spring-Tool-Suite/blob/master/STS-IMG-Github/Screenshot%20(4).png)
![Actuator](https://github.com/NachoEspejo/DEMO-Spring-Tool-Suite/blob/master/STS-IMG-Github/Screenshot%20(5).png)


### Creación de la .Class y modificación
* Desplegamos la _carpeta_ que hemos creado previamente, vamos a _src/main/java_, **_click derecho_** en el _package_, nos dirigimos a **_New_**, **_Class_**.

![Class](https://github.com/NachoEspejo/DEMO-Spring-Tool-Suite/blob/master/STS-IMG-Github/Screenshot%20(10).png)

* Dentro de la .java que hemos creado previamente introducimos el siguiente código:
```
import org.springframework.stereotype.Controller;
import org.springframework.web.bind.annotation.RequestMapping;
import org.springframework.web.bind.annotation.ResponseBody;

@Controller
public class DemoGreetings {
	
	@RequestMapping("/greeting")
	public @ResponseBody String greeting() {
		return "Hello World";
	}
```
![ClassINFO](https://github.com/NachoEspejo/DEMO-Spring-Tool-Suite/blob/master/STS-IMG-Github/Screenshot%20(14).png)


