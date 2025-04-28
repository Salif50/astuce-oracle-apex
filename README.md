# astuce-oracle-apex

## Dynamic action save IG
apex.region( "id_ig" ).widget().interactiveGrid( "getActions" ).invoke("save" );
