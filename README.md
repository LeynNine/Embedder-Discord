# Embedder-Discord
Easy create embed, standardization embeds 

:white_check_mark: Example use:
```py
@client.command()
async def hello(ctx):
  await ctx.send( 
    embed = embed_succes(
      title="Hello!",
      description="My name is ..., i created by ...",
      image="EXAMPLE_URL",
      thumbnail="EXAMPLE_URL",
      footer="thx dude",
      colour=EXAMPLE_COLOR
      
  )
)
```
