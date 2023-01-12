import telebot

bot = telebot.Telebot("5827188753:AAGFhbLuPlwDXsXSDWqZ6r53hM__tBmo-Ao")

@bot.message_handler(content_types=['text'])
def text (message):
    bot.send_message(message.from_user.id, message.text)
   
bot.infinity_polling(timeout=10, long_polling_timeout = 5)
