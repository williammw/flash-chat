
#### implememt multiple class

```
void main() {
  //Animal().move();
  //Bird().move();
  Duck().swim();
}

class Animal{
  @override
  void move(){
    print('change position');
  }
}

class Fish extends Animal{
  @override
  void move(){
    super.move();
    print('by swimming');
  }

}

class Bird extends Animal{
  @override
  void move(){
    super.move();
    print('by Flying');
  }
}

mixin CanSwim{
  void swim(){
    print('changin position by flying');
  }
}

mixin CanFly{
  void fly(){
    print('changin position by flying');
  }
}

class Duck extends Animal with CanSwim , CanFly {

}
```

#### make use of Flutter Outline and refactor,
#### componenet right click -> wrap,delete,....

#### change properties to constants,
