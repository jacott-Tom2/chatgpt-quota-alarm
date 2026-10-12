markdown                                                                                                  
   # ChatGPT Quota Alarm                                                                                      
                                                                                                              
   Alarme Pi pour surveiller l’utilisation du quota ChatGPT.                                                  
                                                                                                              
   ## Fonctionnement                                                                                          
                                                                                                              
   - Seuil d’alerte : 50 % utilisés                                                                           
   - Vérification : toutes les 5 minutes                                                                      
   - Fenêtres surveillées : quota de 5 heures et quota hebdomadaire                                           
   - Notification Pi lorsque le seuil est dépassé                                                             
                                                                                                              
   ## Commandes Pi                                                                                            
                                                                                                              
   ```text                                                                                                    
   /codex alarm status                                                                                        
   /codex alarm 50 5                                                                                          
   /codex alarm off                                                                                           
 ```                                                                                                          
                                                                                                              
 Endpoint utilisé                                                                                             
                                                                                                              
 ```text                                                                                                      
   https://chatgpt.com/backend-api/wham/usage                                                                 
 ```                                                                                                          
                                                                                                              
 Sécurité                                                                                                     
                                                                                                              
 La configuration locale se trouve dans :                                                                     
                                                                                                              
 ```text                                                                                                      
   ~/.pi/agent/codex-accounts.json                                                                            
 ```                                                                                                          
                                                                                                              
 Les tokens ne doivent jamais être commités.                                                                  
                                                                                                              
 Ce projet est indépendant du dépôt App-Révision.
