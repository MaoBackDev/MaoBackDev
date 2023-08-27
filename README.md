### Hi I'm mauricio 👋
<!--
```js
const getMaoBackDev = async (req, res) => {
  const { username } = req.body
  try {
    const mao = await User.findByPk( { where: { username } } )
    if(mao) return res.status(200).json({
      ok: true,
      message: 'You have been lucky',
      mao
    })
  } catch (error) {
    res.status(500).json( { message: error.message } )
  }
```


**MaoBackDev/MaoBackDev** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
