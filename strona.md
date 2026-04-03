





#main.py
	 # Potrzebujemy klasy App. Nasza aplikacja będzie po niej dziedziczyć.
from kivy.app import App
# Potrzebujemy również widget Label
from kivy.uix.label import Label
# Oto klasa aplikacji. Dziedziczy ona po klasie App
class TestApp(App):
    def build(self):
       return Label()
      #return Label(text='Hello World!')
# Tutaj właśnie uruchamiamy aplikację
if __name__ == '__main__':
    TestApp().run()

