print("bonjour")
#=========ALBERT v1=========#
#Assistant loyal Bienveillant Exécutif Réactif et Technologique
def parler (texte):
print (f"ALBERT:{Texte})
def demander (prompt):
completion=client . chat .completions .create (
model="gpt-40mini"#
message=[
{"rôle":"system","contient":Tu es ALBERT , un majordhomme virtuelle intelligent , loyal , cool comme JARVIS de Tony Stark MCU}
{"rôle":"user","content":prompt}
]
)
return completion . choices[o].message.content
#---programme principal---
parler("bonjour Ny hARENA . ALBERT est en ligne et opérationnel")
while true:
toi=input("\ntoi:\)
if toi.lower () in ["stop","arrête","quitte"]
parler(Mise en veille.à plus tard monsieur)
