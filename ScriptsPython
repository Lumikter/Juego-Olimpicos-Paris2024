--- Distribucion de Medallas por Edad ---

import pandas as pd
import matplotlib as mpt
import matplotlib.pyplot as plt

import seaborn as sns

custom_palette = {
    'Gold Medal': '#002654',
    'Silver Medal': '#ED2939',
    'Bronze Medal': 'purple'
}

sns.scatterplot(
    data=dataset,
    x='edad',
    y='cod_atleta',
    hue='tipo_medalla',
    size='clasificacion_edad',
    palette=custom_palette
)

plt.xlabel('Edad', fontsize=12, fontfamily='DIN', color='black') 
plt.ylabel('Nro Atletas', fontsize=12, fontfamily='DIN', color='black')  

plt.axvline(
    x=17, color='black', linestyle='--'
)
plt.axvline(
    x=29, color='black', linestyle='--'
)
plt.axvline(
    x=49, color='black', linestyle='--'
)
plt.show()


--- Distribucion de Medallas por Continente y Deporte

import pandas as pd
import matplotlib as mpt
import matplotlib.pyplot as plt

import seaborn as sns

dataset = dataset.pivot_table(values='codigo_medalla',index='continente', columns='deporte_e')

plt.figure(figsize=(15, 3))
plt.yticks(rotation=90)
sns.heatmap(data=dataset,linewidths=0.5,cmap=sns.cubehelix_palette(as_cmap=True))
plt.subplots_adjust(left=0.05, right=1.12, top=0.95, bottom=0.25) 
plt.show()
