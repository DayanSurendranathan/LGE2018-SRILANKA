###===WORKSPACE===###

#Determine working directory, assign an object to it
work.d <- getwd()

#Define with a vector, the names of the folders
output.folders <- c("1.Raw.Data","2.Clean.Data", "3.Analysis",
                    "4.Graphs", "5.Tables")

#Check to see if folders exist, if not, create function to create them

# This loop checks goes through the given out.put.folders list and checks to
# see if theyexisit in the working directory.
# If they don't they print "does not exist" and creates them,
# if it does exist it prints "does exist"

for(i in 1:length(output.folders)){
  if(!file.exists(output.folders[i])){
    print(paste(i, "does not exist"))
    dir.create(output.folders[i])
  }
  else  {
    print(paste(i,"does exist"))
  }
}

#Setup the pathways

path.rd <- paste(work.d,"/",output.folders[1], "/", sep="") #rawdata

path.cd <- paste(work.d,"/",output.folders[2], "/", sep="") #cleandata

path.a <- paste(work.d,"/",output.folders[3], "/", sep="") #analysis

path.g <- paste(work.d,"/",output.folders[4], "/", sep="") #graphs

path.t <- paste(work.d,"/",output.folders[5], "/", sep="") #tables

