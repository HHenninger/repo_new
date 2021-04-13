# repo_new
import rospy
import matlibplot

def DynNew(Y,t):
u1= 0.5
u2 = 0
return [Y[1], Y[0]*Y[3]**2 + u1, Y[3], -Y[1]*Y[3]/Y[0]+u2/Y[0]]
