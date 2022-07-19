class Rectangle:
    def __init__(self, width, height):
        self.width = width
        self.height = height
    
    def __repr__(self):
        return f"Rectangle(width={self.width}, height={self.height})"
   


    def set_height(self,height):
         self.height = height
   


    def set_width(self):
        self.width = width
    
        
    def get_area(self):
        area = int(self.height * self.width)
        return area 
    

    def get_perimeter(self):
        perimeter = int(2*self.width + 2*self.height)
        return perimeter
    
       
    def get_diagonal(self):
        diagonal = ((self.width ** 2 + self. height ** 2) ** .5)
        return diagonal
    
    
    
    def get_picture(self):
        if self.width > 50 or self.height > 50:
            return "Too big for picture"
        
        for h in range (self.height):
            for w in range (self.width):             
                print('*', end = " ")
            print()
    
    def get_amount_inside(self, box1):
        i_area = box1.get_area()
        j_area = self.get_area()
        return j_area//i_area

class Square(Rectangle): 
    def __init__(self,length):
        super().__init__(length,length)
        
        
    
    
    
    def __repr__(self):
        return f"Square(side={self.width})"
   
    
            
    def set_side(self,length):
        self.width = length
        self.length = length
   
        
    def set_width(self,length):
        self.width = length
   
    def set_height(self,length):
        self.height = length
       
    
           
            
    
