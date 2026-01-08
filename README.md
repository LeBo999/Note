def note_zu_text(note):
    if note == 1 or 2:
       return "gut"

    elif note == 3 or 4:
        return "befriedigend"

    elif note == 5 or 6:
        return "ungenügend"

    else:
        return "Bitte geben Sie eine Note zwischen 1 und 6 ein."

note = int(input("Geben Sie eine Note zwischen 1 und 6 ein: "))
print(f"Die Note {note} bedeutet: {note_zu_text(note)}")
