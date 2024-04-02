# lions
class Lion:
    def __init__(self, name, age, gender):
        self.name = name
        self.age = age
        self.gender = gender

    def roar(self):
        return "Roarrr!"

    def info(self):
        return f"Name: {self.name}, Age: {self.age}, Gender: {self.gender}"


def main():
    lion1 = Lion("Simba", 5, "Male")
    lion2 = Lion("Nala", 4, "Female")

    print("Lion 1:", lion1.info())
    print("Lion 1 says:", lion1.roar())

    print("Lion 2:", lion2.info())
    print("Lion 2 says:", lion2.roar())


if __name__ == "__main__":
    main()
