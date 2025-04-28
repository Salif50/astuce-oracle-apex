# astuce-oracle-apex

## Dynamic action save IG
apex.region( "id_ig" ).widget().interactiveGrid( "getActions" ).invoke("save" );

## ADD NEW ROW
apex.region( "GRID_AGENT" ).widget().interactiveGrid( "getActions" ).invoke( "selection-add-row" );
 
