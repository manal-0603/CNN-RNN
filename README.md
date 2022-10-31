{
  "cells": [
    {
      "cell_type": "markdown",
      "metadata": {
        "id": "view-in-github",
        "colab_type": "text"
      },
      "source": [
        "<a href=\"https://colab.research.google.com/github/manal-0603/CNN-RNN/blob/main/Human_Action_Recogntion_using_CONV_LSTM_And_LRCN.ipynb\" target=\"_parent\"><img src=\"https://colab.research.google.com/assets/colab-badge.svg\" alt=\"Open In Colab\"/></a>"
      ]
    },
    {
      "cell_type": "markdown",
      "metadata": {
        "id": "VuI3Z8l1Ps8a"
      },
      "source": [
        "\n",
        "# **<center><font style=\"color:rgb(100,109,254)\">La reconnaissance des actions humaines (CNN + LSTM)</font> </center>**"
      ]
    },
    {
      "cell_type": "markdown",
      "metadata": {
        "id": "mqVwu2LHKYNF"
      },
      "source": [
        "\n",
        "- **`Step 1:` Télécharger et visualiser les données avec ses étiquettes**\n",
        "\n",
        "- **`Step 2:` Prétraiter l'ensemble de données**\n",
        "\n",
        "- **`Step 3:` Diviser les données en ensemble d'apprentissage et de test**\n",
        "\n",
        "- **`Step 4:` Mettre en œuvre l'approche ConvLSTM**\n",
        "\n",
        "    - **`Step 4.1:` Construire le modèle**\n",
        "    \n",
        "    - **`Step 4.2:`  Compiler et entrainer le modèle**\n",
        "    \n",
        "    - **`Step 4.3:` Tracer les courbes Loss & Accuracy Curves**\n",
        "\n",
        "- **`Step 5:` Mettre en œuvre l'approche LRCN**\n",
        " \n",
        "    - **`Step 5.1:` Construire le modèle**\n",
        "    \n",
        "    - **`Step 5.2:` Compiler et entrainer le modèle**\n",
        "    \n",
        "    - **`Step 5.3:`  Tracer les courbes Loss & Accuracy Curves**\n",
        "    \n",
        "- **`Step 6:`  : Tester le modèle le plus performant sur des vidéos YouTube**\n"
      ]
    },
