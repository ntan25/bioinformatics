file = open('.txt', 'r')
read_file = file.read()
target = 'AGCTAGC'
new_target = (list(target))
stringer = (list(read_file))
indices = []

def searcher(dna_string, target_string):
    for i in range(0, len(dna_string)):
        if target_string == dna_string[i: i + len(target_string)]:
            indices.append("{} to {}".format(i, i + len(target_string)))
            i += 1
        else:
            i += 1
            continue
    return indices
print(searcher(stringer, new_target))
