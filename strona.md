





# Nazwa pliku: test.py
# Potrzebujemy klasy App. Nasza aplikacja będzie po niej dziedziczyć.
from kivy.app import App
# Potrzebujemy również widżetu Label.
from kivy.uix.label import Label
# Oto klasa aplikacji. Dziedziczy ona po App. class TestApp(App):
    def build(self):
# Zwracana jest etykieta.
return Label(text='Hello World!')
# I tutaj właśnie uruchamiamy aplikację. if __name__ == '__main__':
    TestApp().run()
