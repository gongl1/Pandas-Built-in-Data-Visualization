# Pandas-Built-in-Data-Visualization

There are several plot types built-in to pandas, most of them statistical plots by nature:

df.plot.area

df.plot.barh

df.plot.density

df.plot.hist

df.plot.line

df.plot.scatter

df.plot.bar

df.plot.box

df.plot.hexbin

df.plot.kde

df.plot.pie


# c value is shown by size.

df1.plot.scatter(x='A',y='B',s=df1['C']*200)

# Create an area plot of all the columns for just the rows up to 30.

df3.iloc[0:30].plot.area(alpha=0.4)

plt.legend(loc='center left', bbox_to_anchor=(1.0, 0.5))


