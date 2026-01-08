def note_zu_text(note):
    if note in (1, 2):
        return "gut"
    elif note in (3, 4):
        return "befriedigend"
    elif note in (5, 6):
        return "ungenügend"
    else:
        return "Bitte geben Sie eine Note zwischen 1 und 6 ein."
