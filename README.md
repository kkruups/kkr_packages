# kkr_packages 
Package Contents

**kkutils**

      Used to solve issue with RNeo4j  knowledge graph database library when proxy blocks localhost connections.
      But can be used for generic use where localhost connections are blocked by proxy

  **setLclhostEn(http_msg = FALSE)** 
      
      sets system's localhost to not use proxy and sets the System Language environment to english
        
         @http_msg parameter can be set to TRUE, for http logging, FALse, for no http logging
        
         default is FALSE
         
         Examples:
         
         setLclhostEn()
         setLclhostEn(http_msg = TRUE)
         
  **To install**
  
         install.packages(devtools)
         library(devtools)
         install_github(kkruups/kkutils)

