	Prerequisiti:
	- UML2 Extender SDK Developer Resources
	- QVT Operational SDK 
	- Papyrus Software Designer 2.1.0.
	
	
	Come avviare il progetto:
	- Importare il progetto nell'IDE.
	- selezionare il file Uml2asmRia.qvto
	- selezionare Run As/Run Configurations...
	- selezionare 'QVT Operational Transformation' 
	- cliccare  'New launch configuration'.
	- selezionare il modello (estensione .uml) nel campo Model. I modelli .uml si trovano in input_models/use_case*/*.uml
	- Run

	Organizzazione directories:
	- ecores: ecores di asmRia e dei types UMl
	- input_models: casi d'uso generati
	- out: modelli asmRia ottenuti dalla trasformazione dei 3 casi d'uso analizzati
	- asmRia_metamodel: metamodello asmRia
	- profile: profilo asmRia .
	- transforms: file trasformazioni in QVTo.
	- transformations_conf: launch configurations dei 3 diagrammi uml
	