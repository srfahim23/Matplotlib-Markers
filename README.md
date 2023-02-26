# Matplotlib-Markers
# Markers
You can use the keyword argument marker to emphasize each point with a specified marker:

Example

Mark each point with a circle:

    import matplotlib.pyplot as plt
    import numpy as np

    ypoints = np.array([3, 8, 1, 10])

    plt.plot(ypoints, marker = 'o')
    plt.show()

Note:You can see the result in the top a picture i included

Example

Mark each point with a star:

    '''
    plt.plot(ypoints, marker = '*')

Note: You can see the result in the second once picture i included

# Marker Reference
You can choose any of these markers:

    Marker          Description

    'o'             Circle

    '*'             Star

    '.'             Point

    ','             Pixel

    'x'             X

    'X'             X (filed)

    '+'             Plus

    'p'             Plus (filed)

    's'             Square

    'D'             Diamond

    'd'             Diamond (thin)

    'p'             Pentagon

    'H'             Hexagon

    'h'             Hexagon

    'v'             Triangle Down

    '^'             Triangle Up

    '<'             Triangle Left

    '>'             Triangle Right

    '1'             Tri Down

    '2'             Tri up

    '3'             Tri Left

    '4'             Tri Right

    '|'             Vline

    '_'             Hline


    
