# bot-prueba
este fue un proyectoi hecho por mi para mi tarea de kodland
import random


def gen_pass(pass_length):
    elements = "+-/*!&$#?=@<>"
    password = ""

    for i in range(pass_length):
        password += random.choice(elements)

    return password


def gen_emodji():
    emodji = ["\U0001f600", "\U0001f642", "\U0001F606", "\U0001F923"]
    return random.choice(emodji)

def frutas_buenas():
    frut = ["piña", "manzana", "pera", "uva"]
    return random.choice(frut)

def flip_coin():
    flip = random.randint(0, 2)
    if flip == 0:
        return "HEADS"
    else:
        return "TAILS"
