<p align="center">
  <img width="140" src="https://user-images.githubusercontent.com/6661165/91657958-61b4fd00-eb00-11ea-9def-dc7ef5367e34.png" />  
  <h2 align="center">Github Profile Trophy</h2>
  <p align="center">🏆 Add dynamically generated GitHub Trophy on your readme</p>
</p>
<p align="center">
  <a href="https://github.com/ryo-ma/github-profile-trophy/issues">
    <img src="https://img.shields.io/github/issues/ryo-ma/github-profile-trophy"/> 
  </a>
  <a href="https://github.com/ryo-ma/github-profile-trophy/network/members">
    <img src="https://img.shields.io/github/forks/ryo-ma/github-profile-trophy"/> 
  </a>  
  <a href="https://github.com/ryo-ma/github-profile-trophy/stargazers">
    <img src="https://img.shields.io/github/stars/ryo-ma/github-profile-trophy"/> 
  </a>
    <a href="https://github.com/ryo-ma/github-profile-trophy/LICENSE">
    <img src="https://img.shields.io/github/license/ryo-ma/github-profile-trophy"/> 
  </a>
</p>


# Demo

<img width="665" src="https://user-images.githubusercontent.com/6661165/91659339-ed7f5700-eb09-11ea-9d6f-75bd16baf454.png">

# Quick Start

Add following code to your readme.  
Change the `?username=` value to your GitHub's username.

```
[![trophy](https://github-profile-trophy.vercel.app/?username=ryo-ma)](https://github.com/ryo-ma/github-profile-trophy)
```

<img src="https://github-profile-trophy.vercel.app/?username=ryo-ma&column=7&rank=SSS,SS,S,AAA,AA,A,B,C" />

# About Rank

Ranks are `SSS` `SS` `S` `AAA` `AA` `A` `B` `C` `UNKNOWN` `SECRET`.

|  Rank  |  Description  |
| ---- | ---- |
|  SSS, SS, S  | You are hard to reach the rank. You can brag.  |
|  AAA, AA, A  | You can reach the rank if you do your best. Let's aim here first.  |
|  B, C  | You are a growing process.  |
| UNKOWN | You have not yet taken action. Let's act first. |
| SECRET | The rank is very rare. The trophy will not be displayed until the conditions are met. |

## Secret Rank
The acquisition condition is secret, but you can know the condition by reading this code.

<img width="110" src="https://user-images.githubusercontent.com/6661165/91643641-28cd4780-ea70-11ea-94a9-a51885252700.png" />


There are still few secret trophies.  
Therefore, if you come up with interesting conditions, I am waiting for contributions.

# About Display details

<img width="220" src="https://user-images.githubusercontent.com/6661165/91642962-6333e600-ea6a-11ea-83af-e371e996bfa6.png" />

1. Title name of aggregation target.
2. Current Rank.
3. Title according to rank.
4. Target aggregation result.
5. Next Rank Bar. The road from the current rank to the next rank.


# Optional Request Parameters

* [title](#filter-by-titles)
* [rank](#filter-by-ranks)
* [column](#specify-the-maximum-row--column-size)
* [row](#specify-the-maximum-row--column-size)

## Filter by titles

You can filter the display by specifying the titles of trophy.  

```
https://github-profile-trophy.vercel.app/?username=ryo-ma&title=Follower
```
<img width="110" src="https://user-images.githubusercontent.com/6661165/91659424-5535a200-eb0a-11ea-869f-29c83cb4e3c4.png">


If You want to specify multiple titles.

```
https://github-profile-trophy.vercel.app/?username=ryo-ma&title=Star,Follower
```

## Filter by ranks

You can filter the display by specifying the ranks.  
`Available values: SECRET SSS SS S AAA AA A B C`

```
https://github-profile-trophy.vercel.app/?username=ryo-ma&rank=S
```

<img width="110" src="https://user-images.githubusercontent.com/6661165/91642657-1cdd8780-ea68-11ea-994b-4568a55cd22a.png" />

If You want to specify multiple ranks.

```
https://github-profile-trophy.vercel.app/?username=ryo-ma&rank=S,AAA
```


## Specify the maximum row & column size

You can specify the maximum row and column size.  
Trophy out of limits will not be displayed.

`Available value: number type`  
`Default: column=6 row=3`

Restrict only row
```
https://github-profile-trophy.vercel.app/?username=ryo-ma&row=2
```

Restrict only column
```
https://github-profile-trophy.vercel.app/?username=ryo-ma&column=2
```

Restrict row & column
```
https://github-profile-trophy.vercel.app/?username=ryo-ma&row=2&column=3
```
<img width="330" src="https://user-images.githubusercontent.com/6661165/91659474-c07f7400-eb0a-11ea-84f2-eb6b42547829.png">

