# Introduction

This is the first paragraph of the introduction chapter.

## First

This is the first subsection. Please, admire the gloriousnes of Figure \ref{seagull_image}.


## Images
Store images in the images forlder, in a subfolder conmtainiong the chsaopter number (such as Chapter_01), and rename the images with numbers startwing with image_01 for the first image in the chapter.

![Caption.\label{label}](images/Chapter_01/image_01.png)

## Second

This is the second subsection.

Please, check [First] subsection.

Please, check [this](#first) subsection.

Please, check Table \ref{example_table}.

| Index | Name |
| ----- | ---- |
| 0     | AAA  |
| 1     | BBB  |
| ...   | ...  |

Table: This is an example table.\label{example_table}

## Third

Formula example: $\mu = \sum_{i=0}^{N} \frac{x_i}{N}$

Now, full size:

$$\mu = \sum_{i=0}^{N} \frac{x_i}{N}$$

And a code sample:

```rb
def hello_world
  puts "hello world!"
end

hello_world
```

Check these unicode characters: ǽß¢ð€đŋμ
