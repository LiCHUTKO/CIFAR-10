# CIFAR-10 Image Classification 🖼️

Ten projekt demonstruje klasyfikację obrazów z użyciem sieci neuronowej typu CNN (Convolutional Neural Network) na zbiorze danych CIFAR-10. Projekt jest zaimplementowany w języku Python z użyciem bibliotek TensorFlow i Keras.

## Spis treści 📑
- [Wymagania](#wymagania)
- [Instalacja](#instalacja)
- [Struktura projektu](#struktura-projektu)
- [Opis notebooka](#opis-notebooka)
- [Uruchomienie](#uruchomienie)
- [Wyniki](#wyniki)
- [Autor](#autor)

## Wymagania 🛠️

- Python 3.6 lub nowszy
- TensorFlow 2.x
- Keras
- NumPy
- Matplotlib
- PIL (Python Imaging Library)

## Instalacja 💻

1. Sklonuj repozytorium:
    ```sh
    git clone https://github.com/LiCHUTKO/CIFAR-10.git
    cd CIFAR-10
    ```

2. Zainstaluj wymagane pakiety:
    ```sh
    pip install -r requirements.txt
    ```

## Struktura projektu 📂

```
.
├── notebook.ipynb
├── README.md
└── requirements.txt
```

 
## Opis notebooka 📓

### Załadowanie potrzebnych bibliotek

Importujemy niezbędne biblioteki do budowania i trenowania modelu oraz do wizualizacji danych.

### Załadowanie i normalizacja danych

Ładujemy zbiór danych CIFAR-10 i normalizujemy dane, przeskalowując wartości pikseli do zakresu [0, 1].

### Tworzenie modelu

Definiujemy model sieci neuronowej typu CNN z użyciem Keras.

### Kompilacja i trenowanie modelu

Kompilujemy model, określając optymalizator, funkcję straty i metryki, a następnie trenujemy model na danych treningowych.

### Wizualizacja krzywych uczenia

Tworzymy wykresy strat i dokładności dla danych treningowych i walidacyjnych.

### Ewaluacja modelu

Oceniamy wytrenowany model na zestawie testowym, obliczając stratę i dokładność.

### Wizualizacja predykcji

Wykonujemy predykcje na zestawie testowym i wyświetlamy obrazy wraz z przewidywanymi i rzeczywistymi etykietami.

### Przetwarzanie i przewidywanie obrazu

Ładujemy obraz, przetwarzamy go, a następnie używamy wytrenowanego modelu do przewidywania etykiety dla tego obrazu.

## Uruchomienie 🚀

1. Otwórz  w Jupyter Notebook lub JupyterLab.
2. Uruchom wszystkie komórki, aby załadować dane, zbudować i wytrenować model, a następnie ocenić jego wydajność.

## Wyniki 📊

Model osiąga dokładność około 70% na zestawie testowym CIFAR-10. Poniżej znajdują się przykładowe wykresy i predykcje:

## Autor ✍️

- LiCHUTKO (https://github.com/LiCHUTKO)
