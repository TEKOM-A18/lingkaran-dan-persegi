class Lingkaran(object):
  def __init__(self,r):
    self.r=r
    self.phi=3.14
  def hitungLuas(self):
    return self.phi*self.r*self.r
  def hitungKeliling(self):
    return2*self.phi*self.r
    
def main():
  lingkaran=Lingkaran(4)
  
  print("Luas Lingkaran")
  print("phi\t:",lingkaran.phi)
  print("r\t:",lingkaran.r)
  print("Luas\t=",lingkaran.hitungLuas())
  
  lingkaran2=Lingkaran(7)
  
  print("\nKeliling Lingkaran")
  print("phi\t:",lingkaran2.phi)
  print("r\t:",lingkaran2.r)
  print("Luas\t=",lingkaran2.hitungKeliling())
if __name__=="__main__":
  main()
  
class Persegi(object):
  def__init__(self,s):
    self.s=s
   def hitungluas(self):
    return self.s*self.s
   def hitungKeliling(self):
    return 4*self.s
    
def main():

  persegi=Persegi(9)
  
  print("\nLuas Persegi")
  print("Sisi\t:",persegi.s)
  print("Luas\t=",persegi.hitungLuas())
  
  persegi2=Persegi(6)
  
  print("\nKeliling Persegi")
  print("Sisi\t:",persegi.s)
  print("Luas\t=",persegi.hitungKeliling())
  
if __name__=="__main__':
  main()
