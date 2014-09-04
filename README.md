# Reminder-Me

A simple Python web service to generate RSS feeds for recurring
reminders.

Ever need recurring reminders to do simple things, but always forget
to do it? Hate trying to deal with various reminder apps, but live in
an RSS reader for everything anyway?  Reminder-Me might be for you!

What this does is generates an RSS feed which will remind you to do
something after a certain period of time.  If you ignore the reminder,
it'll keep on reminding you until you say you've done the thing (as
long as your feed reader shows images, anyway).

It's good for things that you need to be reminded of when you're
otherwise reading your RSS feeds; cleaning the cat box, doing your
laundry, watering the plants, that sort of thing.  It's perfect for
errands which need to happen at a certain rough interval but which
don't necessarily need to happen at a specific time of day or week.

## Installation

You just need the following:

* An ordinary CGI-enabled directory which serves up `.cgi` files as
  CGI scripts (ideally running with suexec)
* [peewee](https://github.com/coleifer/peewee) installed (using `pip`
  or whatever installation mechanism you prefer)

To install or upgrade, just point your browser at `install.cgi`, and
then you can start making reminder feeds. That's it!
