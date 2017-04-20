# Using Deep Structured Semantic Model for question answering
In http://dl.acm.org/citation.cfm?id=2505665 DSSM was proposed. General idea is finidng a deep vector representation for objects. In my work I try to adapt this idea for question&answering problems. LSTM and triplet loss are being combined for  

The idea of finiding vector representation of data is not new. Encoder-decoder (link!) models and seq2seq (link!) modeling also try to find a latent space. In my work I try to find out if there is way of building a unversal latent space and corresponding set of transformations for different kinds of objects, such that vector from latent space can represent those objects. This idea allows to build different pipelines for any kind of problem with the data.

![pic](https://www.draw.io/?lightbox=1&edit=_blank&layers=1&nav=1&title=dream_model.xml#R5VlbU%2BMgGP01fXWaC9g%2BtmrdB51xpg%2B7%2B4gJTVhpqJTe9tcvBHKDWGON2lk7oxMOhJBzzvflIxkEV8v9LUer9J7FmA78YbwfBNcD3x9BKP8r4KCBMAg1kHASa8irgDn5iw04NOiGxHjdGCgYo4KsmmDEsgxHooEhztmuOWzBaPOqK5RgB5hHiLroTxKL1NwWGFb4D0yStLiyNzQ9jyh6SjjbZOZ6Az9Y5D%2FdvUTFXGb8OkUx29Wg4GYQXHHGhD5a7q8wVdQWtOnzZi%2F0luvmOBNdTvD1CVtEN%2BbWJ2Zh4lCQkd8OVid4g2C6S4nA8xWKVO9Oqi%2BxVCyp6XYXYNa0xVzgfQ0yC7rFbIkFP8ghRe%2FYkHMo2dXtXSWFVxCY1mSABkNG%2FaScumJAHhgS2gkJHEKmZ0dIeaOfQUjoEOLwgbN4ooJOtiKK1msSNSnAeyJ%2B1Y5%2Fy%2BPhBVCtTK7mV970YNE23WX%2FA%2BZELhtzhUuwjJmj9K7Zhke4IapAPMFmFNAQjhuJwJWgRjFoYbjAOKZIkG0zfbTRbq7wwIhc74sKB2NLOX035qx6PFsT%2BaE1UWhNpDlwJspdUN52J2MAxxh3SCgVfIiWKgiyx%2FUqVwhSydY0Jlt5mIgatF6hrMB0BJkOee16XwE%2FchuRAxvz2s6kVD4ysDbNCucGZZv4U6I2tKTwLjtG7aiHqB27VEinz02TcZGyhGWI3lTotEprw%2Fb4NTFrIthrxi%2Boh69nh%2BkfLMTBPOfRRjAJVYu4Y2z1Gu%2BvBuo7I7CMZKMW8E%2BNwNcm6i8CvcKT78jNDZV6TtSdcrN%2F7rk5sAT1Ts3N4dCa6ONys%2BeWMf04Y3gxugSuO2TLFr9yjGWXrsYArjG88KycAW1Bx%2BA0Z8CR7Qxroh6d4dZzX1%2Fxw6%2Bs%2BD23kPn6kt9m5FNLfu%2Fy%2F8we5%2FVcAYEl8anPFWBlD%2F%2FjniuF4445402hsiCUXjHKlO4Zy1QZmnAUEymtBXMmJNssUycqF6wFZ0%2B4GDTwg9kskL%2Byp3hvc9Qxb9iDA9BMUWDsBGSZxtPGu6EjzugakQXNvfHusAfhbAZhK3vdNeqF56aZx27ea6XZDp6TWO5QNb2PZfWbzc6AZWtv2rI1DYMWlnvZm7a%2BUtLb%2BQXLE1tUMgafN0zv7HPu1HvUCtKb%2Fuv5%2FL72OkBP8cL7AEmPOCaRYbhFC0RJonJPJElXT6mpIptEiE5Mx5LEcb6NbvOEWpTZ%2FfqjfiQEVvEZjFo0bJOwDwXdkqmLgotFnqEdBef42Zd%2F31DES1tE8IkiwpNEhHCxUJ93bBEnG8FwFrFYEvsNhbSKuY%2FTUTarz0O6hKs%2BwQU3%2FwA%3D)




## ToDo list
1. Try to train decoder to answer from semantic space
2. Implement GAN for decoder
3. Try decoder to itself
4. Conv
5. Reimplement topics
