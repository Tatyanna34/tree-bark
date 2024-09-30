# tree-barkimport random

def generate_tree_bark(height, width):
    # Characters to simulate tree bark texture
    bark_chars = ['|', '/', '\\', '-', ' ']
    
    for _ in range(height):
        line = ''.join(random.choice(bark_chars) for _ in range(width))
        print(line)

# Example: generate bark with height 20 and width 40
generate_tree_bark(20, 40)
