class Shape:
              def setValue(self,s):
                            self.s=s
class Square(Shape):
              def area(self):
                            return self.s*self.s
class Cube(Shape):
              def volume(self):
                            return self.s*self.s*self.s

sq=Square()
sq.setValue(10)
print("The square of the area",sq.area())

cu=Cube()
cu.setValue(20)
print("The cube of the volume",cu.volume())

