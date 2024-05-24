data["joint_LFCoxa"]=np.concatenate([np.linspace(0.6, 0, 100),np.linspace(0, 0, 100),np.linspace(0, 0, 100),np.linspace(0, 0, 100),np.linspace(0, 0, 100)]).tolist()
data["joint_LFCoxa_roll"]=np.concatenate([np.linspace(0.8, 0, 100),np.linspace(0, 0.8, 100),np.linspace(0.8, 0.8, 100),np.linspace(0.8, 0.8,100),np.linspace(0.8, 0.3, 100)]).tolist()
data["joint_LFCoxa_yaw"]=np.concatenate([np.linspace(0, 1.5, 100),np.linspace(1.5,1.5, 100),np.linspace(1.5,1.5, 100),np.linspace(1.5,1.5, 100),np.linspace(1.5, 1.5, 100)]).tolist()
data["joint_LFFemur"]=np.concatenate([np.linspace(-1.5, -1.5, 100),np.linspace(-1.5,-1.5, 100),np.linspace(-1.5,-1.5, 100),np.linspace(-1.5,-1.5,100),np.linspace(-1.5, -1.5, 100)]).tolist()
data["joint_LFFemur_roll"]=np.concatenate([np.linspace(0.3, -1.5, 100),np.linspace(-1.5,-1.5, 100),np.linspace(-1.5,-1.5,100),np.linspace(-1.5,-1.5, 100),np.linspace(-1.5,-1.5, 100)]).tolist()
data["joint_LFTibia"]=np.concatenate([np.linspace(1, -1.17, 100),np.linspace(-1.17,-1.1, 100),np.linspace(-1.1,-1.1 ,100),np.linspace(-1.1,-1.1, 100),np.linspace(-1.1, -0.9, 100)]).tolist()
data["joint_LFTarsus1"]=np.concatenate([np.linspace(-0.5, -1.5, 100),np.linspace(-1.5,-0.21 ,100),np.linspace(-0.2,0, 100),np.linspace(0,0, 100),np.linspace(0, -0.6, 100)]).tolist()

data["joint_LMCoxa"]=np.concatenate([np.linspace(0.11, 0.11, 100),np.linspace(0.11,0.12, 100),np.linspace(0.12,0.8, 100),np.linspace(0.8,1, 100),np.linspace(1, -0.6, 100)]).tolist()
data["joint_LMCoxa_roll"]=np.concatenate([np.linspace(1.6, 0.1, 100),np.linspace(0.1,0.1 ,100),np.linspace(0.1,0.1,100),np.linspace(0.1,0.1 ,100),np.linspace(0.1, 0.1, 100)]).tolist()
data["joint_LMCoxa_yaw"]=np.concatenate([np.linspace(0, 0.4, 100),np.linspace(0.4,0.4, 100),np.linspace(0.4,0.4, 100),np.linspace(0.4,0.6, 100),np.linspace(0.6, 0.4, 100)]).tolist()
data["joint_LMFemur"]=np.concatenate([np.linspace(-1.98, -1.98, 100),np.linspace(-1.98,-0.698 , 100),np.linspace(-0.698,-0.428, 100),np.linspace(-0.428,-0.428,100),np.linspace(-0.428, -0.498, 100)]).tolist()
data["joint_LMFemur_roll"]=np.concatenate([np.linspace(0.4, 0, 100),np.linspace(0,0 , 100,),np.linspace(0,0, 100),np.linspace(0,0 , 100),np.linspace(0, 0,100)]).tolist()
data["joint_LMTibia"]=np.concatenate([np.linspace(1.74, 1.74, 100),np.linspace(1.74,0.5, 100),np.linspace(0.5,0.2, 100),np.linspace(0.2,0.2, 100),np.linspace(0.2,1.5, 100)]).tolist()
data["joint_LMTarsus1"]=np.concatenate([np.linspace(-0.59, -0.2, 100),np.linspace(-0.2,-0.33 ,100),np.linspace(-0.33,-0.1, 100),np.linspace(-0.1,-0.1 ,100),np.linspace(-0.1, -1.2, 100)]).tolist()

data["joint_LHCoxa"]=np.concatenate([np.linspace(0.4, 0.4, 100),np.linspace(0.4,0.21, 100),np.linspace(0.21,-0.2, 100),np.linspace(-0.2,-0.2, 100),np.linspace(-0.2, 0.6, 100)]).tolist()
data["joint_LHCoxa_roll"]=np.concatenate([np.linspace(2.58, 2.5, 100),np.linspace(2.5,2.5,100),np.linspace(2.5,2.5, 100),np.linspace(2.5,2.6, 100),np.linspace(2.61, 2.61, 100)]).tolist()
data["joint_LHCoxa_yaw"]=np.concatenate([np.linspace(0, 0, 100),np.linspace(-0.07,0.2,100),np.linspace(0.2,0.2, 100),np.linspace(0.2, 0.2, 100),np.linspace(0.2, 0.4, 100)]).tolist()
data["joint_LHFemur"]=np.concatenate([np.linspace(-2, -1.01, 100),np.linspace(-1.01,-1.82 ,100),np.linspace(-1.82,-1.2, 100),np.linspace(-1.2,-1.2 ,100),np.linspace(-1.2, -0.2, 100)]).tolist()
data["joint_LHFemur_roll"]=np.concatenate([np.linspace(0, 0, 100),np.linspace(0,0 , 100),np.linspace(0,0, 100),np.linspace(0,0 , 100),np.linspace(0, 0, 100)]).tolist()
data["joint_LHTibia"]=np.concatenate([np.linspace(2, 2.07, 100),np.linspace(2.07,2.15, 100),np.linspace(2.15,0.1, 100),np.linspace(0.1,0.1, 100),np.linspace(0.1, 0.1, 100)]).tolist()
data["joint_LHTarsus1"]=np.concatenate([np.linspace(-0.5, -1, 100),np.linspace(-1,-1.1, 100),np.linspace(-1.1,-0.2, 100),np.linspace(-0.2,-0.2,100),np.linspace(-0.2, -0.2, 100)]).tolist()


data["joint_RFCoxa"]=data["joint_LFCoxa"]
data["joint_RFCoxa_roll"]=[-x for x in data["joint_LFCoxa_roll"]]
data["joint_RFCoxa_yaw"]=[-x for x in data["joint_LFCoxa_yaw"]]
data["joint_RFFemur"]=data["joint_LFFemur"]
data["joint_RFFemur_roll"]=[-x for x in data["joint_LFFemur_roll"]]
data["joint_RFTibia"]=data["joint_LFTibia"]
data["joint_RFTarsus1"]=data["joint_LFTarsus1"]

data["joint_RMCoxa"]=data["joint_LMCoxa"]
data["joint_RMCoxa_roll"]=[-x for x in data["joint_LMCoxa_roll"]]
data["joint_RMCoxa_yaw"]=[-x for x in data["joint_LMCoxa_yaw"]]
data["joint_RMFemur"]=data["joint_LMFemur"]
data["joint_RMFemur_roll"]=[-x for x in data["joint_LMFemur_roll"]]
data["joint_RMTibia"]=data["joint_LMTibia"]
data["joint_RMTarsus1"]=data["joint_LMTarsus1"]

data["joint_RHCoxa"]=data["joint_LHCoxa"]
data["joint_RHCoxa_roll"]=[-x for x in data["joint_LHCoxa_roll"]]
data["joint_RHCoxa_yaw"]=[-x for x in data["joint_LHCoxa_yaw"]]
data["joint_RHFemur"]=data["joint_LHFemur"]
data["joint_RHFemur_roll"]=[-x for x in data["joint_LHFemur_roll"]]
data["joint_RHTibia"]=data["joint_LHTibia"]
data["joint_RHTarsus1"]=data["joint_LHTarsus1"]
