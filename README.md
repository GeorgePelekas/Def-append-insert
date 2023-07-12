# Def-append-insert
def fired(estiatorio,onoma):
    if (onoma in estiatorio and estiatorio[0]):
        print("perma ban "+onoma)
def award(Restaurant):
    if (Restaurant[0] > 10 or Restaurant[1] and Restaurant[2]==True):
        print("Restaurant is awarded")
    else:
        print("Restaurant is not awarded")
        
KFC = [100,31,False]
Goodys = [6,28,True]
Volcano=[1,5,True]
award(KFC)
award(Goodys)
award(Volcano)
KFC.append("akis")
Goodys.append("iosif")
Volcano.append("nikos")
if "iosif" in Volcano:
    print("niko fyge")
Volcano.insert(2,"iosif")
print(Goodys)
if "iosif" in Volcano:
    print("niko fyge")
fired(KFC,"menios")
fired(Volcano,"maki")
fired(Goodys,"iosif")    
