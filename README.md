# NewProject1
SimpleCod
# ~ class Car():
	# ~ """простая модель автомобиля"""
	# ~ def __init__(self, make, model, year):
		# ~ self.make = make
		# ~ self.model = model
		# ~ self.year = year
		# ~ self.odometr_reading = 0
	
	# ~ def get_descriptive_name(self):
		# ~ long_name = str(self.year)+ " " + self.make + " " + self.model
		# ~ return long_name.title()
	
	# ~ def read_odometer(self):
		# ~ print("This car has " + str(self.odometr_reading) + " miles on it.")

	# ~ def update_odometer(self, mileage):
		# ~ if mileage >= self.odometer_reading:
			# ~ self.odometer_reading = mileage
		# ~ else:
			# ~ print("You can't roll back an odometr!")
	
	# ~ def increment_odometr(self, miles):
		# ~ self.odometer_reading += miles
# ~ class Battery():#элементы как атрибуты (ввиде отдельного класса)
		# ~ """простая модель аккумулятора в электромобиля."""
		# ~ def __init__(self, battery_size = 70):
			# ~ """инициализирует атрибуты аккумулятора."""
			# ~ self.battery_size = battery_size
		
		# ~ def describe_battary(self):#суб-классу добавили метод
			# ~ """выводит инф о мощности аккумулятора."""
			# ~ print("This car has a " + str(self.batery_size) + "-kWh battery.")
	# ~ #наследование
# ~ class ElecricCar(Car):
		# ~ """представляет аспекты машины, специфические для электромобилей."""
		# ~ def __init__(self, make, model, year):
			# ~ """инициализируем атрибуты класса-родителя"""
			# ~ super().__init__(make, model,year)
			# ~ self.batery_size = 70 #суб-классу добавили аргумент
			# ~ self.battery = Battery()
			
# ~ my_tesla = ElecricCar('tesla', 'model S', 2016)
# ~ print(my_tesla.get_descriptive_name())
# ~ my_tesla.battery.describe_battary()                             

with open('pi_digits.txt') as file_object:
	contents = file_object.read()
	print(contents)






