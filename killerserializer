import random
import string

class serializer():

    def __init__(self):
        pass

    def generate(self):
        x = {x:z for x,z in zip(list(string.ascii_letters)[0:round(len(list(string.ascii_letters)) / 2)], [i for i in range (0, round(len(list(string.ascii_letters)) / 2))]) }
        zx = {z:u for u,z in zip(list(string.ascii_letters)[0:round(len(list(string.ascii_letters)) / 2)], [i for i in range (0, round(len(list(string.ascii_letters)) / 2))]) }
        p = []
        storethat = []
        for z in list(y for y in string.ascii_letters * 3):
            try: p.append(x[z])
            except: pass
        for y in p:
            try: storethat.append(str([i for i in range(1,len(p))][y - random.randint(0,7)] + [i for i in range(1,len(p))][y]))
            except: pass
        zzz = []
        for mm in storethat:
            try: zzz.append("".join([s for s in zx[int(mm)]]))
            except:pass
        zu = "".join(zzz)
        for y in range(0,len(zu), len(zu) // 1):
            pp = list(zu[y: y + len(zu) // random.randint(10,23)][::-1] + zu[y: y + len(zu)][::-1])
            zzx = [x[random.choice(xg)]  for xg in pp]
            plk = {m:j for j,m in zip(list(string.punctuation),range(0, len(list(string.punctuation)) - 5))  }
            kjk = [plk[lkz] for lkz in zzx ]
            kj = [zx[lkz] for lkz in zzx ]
            how = list(kjk) + list(kj)
            how = "".join(set(how))
            chkz = {'key': how}
            return chkz['key']
