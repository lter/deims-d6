Readme           Inigo San Gil, April 2011
======
Here you will find the individual content types used to recreate a fully compliant BDP metadata management system based in Drupal. 

Custom Content Types (and forms)
--------------------------------
There are a dozen content types involved: 
Eleven were made by our group, and an additional one, Biblio, was created installing the "biblio" contributed module.

--Name----------------------------------Machine name------------
Analytical Tool                         software
Biblio                                  biblio
Browse Graphics                         browse_graphics
Entity Information                      data_file
Metadata Record                         data_set
Methodology                             methodology
Person, Organization or Position        person
Planar Coordinate System                planar_coordinate_system
Process Step	                        process_step
Research Site                           research_site
Source Information                      source_info
Variable (Attribute)	                variable

Contrib and Custom Modules
--------------------------
There are a number of contributed modules needed to make this work nicely.  There are also custom modules created by us, 
mostly to create compound CCK fields.

Here is a list of everything I have.
 Package          Name                                        Type    Status         Version     
 - - - - - - - - - - - -  - - -    -    -   -   -   -   -   -  - - - - - - -  -   -  - - - - 
 Administration   Admin Role (adminrole)                       Module  Enabled        6.x-1.3     
 Administration   Administration menu (admin_menu)             Module  Enabled        6.x-1.6     
 Biblio           Biblio (biblio)                              Module  Enabled        6.x-1.15    
 Biblio           Biblio - PubMed (biblio_pm)                  Module  Enabled        6.x-1.15    
 CCK              CCK Fieldgroup Tabs (cck_fieldgroup_tabs)    Module  Enabled        6.x-1.x-dev 
 CCK              Code Value and Code Definition Pair Field    Module  Enabled        6.x-1.0     
                  (codedefinition_fld)                                                            
 CCK              Computed Field (computed_field)              Module  Enabled        6.x-1.0-bet 
                                                                                      a5          
 CCK              Conditional Fields (conditional_fields)      Module  Enabled        6.x-2.0-bet 
                                                                                      a2          
 CCK              Content (content)                            Module  Enabled        6.x-2.9     
 CCK              Content Copy (content_copy)                  Module  Enabled        6.x-2.9     
 CCK              Content Permissions (content_permissions)    Module  Enabled        6.x-2.9     
 CCK              Content Taxonomy (content_taxonomy)          Module  Enabled        6.x-1.0-rc2                                                         
 CCK              Custom Formatters (custom_formatters)        Module  Enabled        6.x-1.5     
 CCK              Email (email)                                Module  Enabled        6.x-1.2     
 CCK              Fieldgroup (fieldgroup)                      Module  Enabled        6.x-2.9     
 CCK              FileField (filefield)                        Module  Enabled        6.x-3.9          
 CCK              ImageField (imagefield)                      Module  Enabled        6.x-3.9     
 CCK              Link (link)                                  Module  Enabled        6.x-2.9     
 CCK              Node Reference (nodereference)               Module  Enabled        6.x-2.9     
 CCK              Node Reference Formatters                    Module  Enabled        6.x-1.2     
                  (nodereference_formatters)                                                      
 CCK              Node Referrer (nodereferrer)                 Module  Enabled        6.x-1.0-rc2 
 CCK              Number (number)                              Module  Enabled        6.x-2.9     
 CCK              Option Widgets (optionwidgets)               Module  Enabled        6.x-2.9     
 CCK              Phone - CCK (phone)                          Module  Enabled        6.x-2.18    
 CCK              Quantitative Attribute Accuracy Assesment    Module  Enabled        6.x-1.0     
                  Field (qaa_fld)                                                                 
 CCK              Quantitative Horizontal Positional Accuracy  Module  Enabled        6.x-1.0     
                  Assesment Field (qhpaa_fld)                                                     
 CCK              Quantitative Vertical Position Accuracy      Module  Enabled        6.x-1.0     
                  Assesment Field (qvpaa_fld)                                                     
 CCK              Spatial Data Transfer Standard (SDTS) Term   Module  Enabled        6.x-1.0     
                  Description Field (sdtsterms_fld)                                               
 CCK              Text (text)                                  Module  Enabled        6.x-2.9     
 CCK              User Reference (userreference)               Module  Enabled        6.x-2.9     
 CCK              Vector Point Format (VPF) Term Description   Module  Enabled        6.x-1.0     
                  Field (vpfterms_fld)                                                                                                                                                   
 Chaos tool suite Chaos tools (ctools)                         Module  Enabled        6.x-1.8     
 Core - optional  Color (color)                                Module  Enabled        6.20        
 Core - optional  Comment (comment)                            Module  Enabled        6.20             
 Core - optional  Database logging (dblog)                     Module  Enabled        6.20               
 Core - optional  Help (help)                                  Module  Enabled        6.20               
 Core - optional  Menu (menu)                                  Module  Enabled        6.20               
 Core - optional  Path (path)                                  Module  Enabled        6.20        
 Core - optional  PHP filter (php)                             Module  Enabled        6.20       
 Core - optional  Search (search)                              Module  Enabled        6.20        
 Core - optional  Taxonomy (taxonomy)                          Module  Enabled        6.20        
 Core - optional  Update status (update)                       Module  Enabled        6.20        
 Core - optional  Upload (upload)                              Module  Enabled        6.20        
 Core - required  Block (block)                                Module  Enabled        6.20        
 Core - required  Filter (filter)                              Module  Enabled        6.20        
 Core - required  Node (node)                                  Module  Enabled        6.20        
 Core - required  System (system)                              Module  Enabled        6.20        
 Core - required  User (user)                                  Module  Enabled        6.20        
 Date/Time        Date (date)                                  Module  Enabled        6.x-2.7     
 Date/Time        Date API (date_api)                          Module  Enabled        6.x-2.7     
 Date/Time        Date Timezone (date_timezone)                Module  Enabled        6.x-2.7      
 Features         bdp_compliant_metadata                       Module  Enabled        6.x-1.0-dev 
                  (bdp_compliant_metadata)                                                        
 Features         Features (features)                          Module  Enabled        6.x-1.0     
 Form Elements    Hierarchical Select (hierarchical_select)    Module  Enabled        6.x-3.7                                                                 
 ImageCache       ImageAPI (imageapi)                          Module  Enabled        6.x-1.9     
 ImageCache       ImageAPI GD2 (imageapi_gd)                   Module  Enabled        6.x-1.9        
 Modal frame      Modal Frame API (modalframe)                 Module  Enabled        6.x-1.7     
 OpenLayers       OpenLayers (openlayers)                      Module  Enabled        6.x-2.0-alp 
                                                                                      ha10        
 OpenLayers       OpenLayers CCK (openlayers_cck)              Module  Enabled        6.x-2.0-alp 
                                                                                      ha10        
 OpenLayers       OpenLayers UI (openlayers_ui)                Module  Enabled        6.x-2.0-alp 
                                                                                      ha10        
 Other            Advanced help (advanced_help)                Module  Enabled        6.x-1.2     
 Other            Backup and Migrate (backup_migrate)          Module  Enabled        6.x-2.4     
 Other            BDP Config (bdp_config)                      Module  Enabled                    
 Other            Diff (diff)                                  Module  Enabled        6.x-2.1     
 Other            getID3() (getid3)                            Module  Enabled        6.x-1.4     
 Other            noderefcreate (noderefcreate)                Module  Enabled        6.x-1.0     
 Other            Search config (search_config)                Module  Enabled        6.x-1.6     
 Other            Tabs (tabs)                                  Module  Enabled        6.x-1.x-dev 
 Other            Token (token)                                Module  Enabled        6.x-1.15     
 User interface   Automodal (automodal)                        Module  Enabled        6.x-1.0     
 User interface   jQuery UI (jquery_ui)                        Module  Enabled        6.x-1.4     
 User interface   jQuery Update (jquery_update)                Module  Enabled        6.x-2.0-alp 
                                                                                      ha1         
 User interface   Modal Node References (modal_noderef)        Module  Enabled        6.x-1.1     
 User interface   onBeforeUnload API (onbeforeunload)          Module  Enabled        6.x-1.0                                           
 User interface   Wysiwyg (wysiwyg)                            Module  Enabled        6.x-2.3         
 Views            Bonus: Views Export (views_bonus_export)     Module  Enabled        6.x-1.1     
 Views            Bonus: Views Export BDP                      Module  Enabled        6.x-1.1     
                  (views_bonus_bdp_export)                                                        
 Views            Views (views)                                Module  Enabled        6.x-2.12    
 Views            Views Custom Field (views_customfield)       Module  Enabled        6.x-1.0     
 Views            Views exporter (views_export)                Module  Enabled        6.x-2.12    
 Views            Views UI (views_ui)                          Module  Enabled        6.x-2.12            
 Views            Views XML (views_xml)                        Module  Enabled        6.x-1.0-beta2      
 Other            Garland (garland)                            Theme   Enabled        6.20   

--------------------------------------------------------------------------------------------------------------------------------



Features
--------
Installing Content types, views and menus manually may be more teaching, but sometimes tedious, 
and prone to some type of errors.     

You may want to check out the features that bundle "most of it".  

What do you mean "most of it"
-----------------------------
Basic tabs labels are not transported, making the forms not render as expencted out of the box.
There is also some fine-tunning with the permissions, sometimes these are not exported automatically,
it is up to you to make them right (CRUDE appropriately or assign view and edit permission per each CCK.)
There are a couple of oddities, this is not an official release as of yet, I expect to have an official
release in Summer 2011.

