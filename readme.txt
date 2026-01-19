Kryptografia Krzywych Eliptycznych (ECC) - Jan Kocierz

W tym repozytorium znajdują się materiały i kody źródłowe towarzyszące mojej prezentacji: "Jak krzywe eliptyczne chronią twoje dane?". Projekt został zrealizowany w ramach działalności Studenckiego Koła Naukowego Matematyków Politechniki Krakowskiej.

Celem tych materiałów jest pokazanie zarówno matematycznych podstaw (krzywe nad ciałami $\mathbb{R}$ i skończonymi), jak i praktycznego zastosowania ECC w nowoczesnych protokołach bezpieczeństwa.

**(Prezentacja_ECC.pdf)**– Slajdy z wystąpienia. Omawiam tam m.in. protokół Diffiego-Hellmana, problem logarytmu dyskretnego oraz standardy takie jak Curve25519 czy TLS 1.3.

**(krzywe_eliptyczne2.ipynb)** (SageMath) – Notatnik skupiony na teorii. Zawiera wizualizacje krzywych eliptycznych nad ciałem liczb rzeczywistych oraz operacje w grupie punktów.

ECC.ipynb (Python) – Praktyczna implementacja. Pokazuję, jak przy użyciu biblioteki cryptography wygenerować klucze i uzgodnić wspólny sekret (ECDH) na krzywej X25519.

Do otwarcia plików .ipynb potrzebujesz środowiska Jupyter Notebook lub Google Colab.

Python (ECC.ipynb):Wymaga zainstalowania biblioteki cryptography. 

SageMath (krzywe_eliptyczne2.ipynb):Ten plik wymaga kernela SageMath. 