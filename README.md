# Morvenger
Sprint Spring MVC ITU S4

Source : 
        Framework :     
                *lib :  *framework.jar
                        *servlet-api.jar
                
                *src :  *mg
                                *itu:
                                        *prom16 :       -FrontServlet.java 
                        *controller:
                                        -TestControllers.java
                                        -Test2Controllers.java
                        *annotation :
                                        -AnnotationControllers.java
                -.gitattributes
                -compress.bat
                -Deployement.bat
                -Morvenger.war
                -Readme.Md
                -Todo.txt
        
        Web :   
                *conf :  --web.xml   
                *lib :  *framework.jar
                        *servlet-api.jar      


Mardi 07 Mai 2024
    Sprint 0:
        -   GitHub:
                Creation Depot
                Branche Sprint 0
                
        -   Script:
                .Jar
                Deployement

        -   FrontController:
                package = mg.itu.prom16.FrontServlet(Controller)
                Doget/DoPost = ProcessRequest {Recuperation des urls}
                Web.xml

    Sprint 1:
        -Annotation:
            AnnotationControllers

        -FrontServlet +=
            getListAnnotation

        -Controller
            TestControllers:Sans Annotation
            Test2Controllers: Avec Annotation

        -Web Xml
            initParam: 
                contextConfigLocation:controller