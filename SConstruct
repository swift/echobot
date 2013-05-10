import os

env = Environment(ENV = {"PATH": os.environ["PATH"]})
env["SWIFTEN_CONFIG"] = "swiften-config"
env.MergeFlags(env.subst("!$SWIFTEN_CONFIG --cflags --libs"))
env.Program("EchoBot.cpp")
