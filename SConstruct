import os

#tex2docx = Builder(action = 'python c:\projects\mc2py\pipetex.py  $SOURCE | pandoc -f latex -o $TARGET',suffix = '.docx',src_suffix = '.tex')
env=Environment(ENV = os.environ)
#env.Append(BUILDERS = {'Tex2docx' : tex2docx})
res = env.PDF("tk_diplom.tex")
#t1=env.Tex2docx("project_support.tex")

