import UIKit

struct Task {
    var title : String
    var descrption : String
    var dueDate : Date?
    var priority : Priority
}

enum Priority {
    case low
    case normal
    case high
}

class TaskManager  {
    
    var Tasks : [Task] = []
    
    func addtask (inputTask : Task){
        
        Tasks.append(inputTask)
        }
    
    
    func displayTasks (){
        
        for value in Tasks {
            print("your Titale \(value.title) , Descrpition \(value.descrption)")
        }
    }
    
    func removeTask (index : Int) {
        
        if (Tasks.count >= index &&  index > 0) {
            Tasks.remove(at: index)
        }
        else {
            print("Please Enter Valid Index Number")
        }
    
    }
    
    
}

var NewTask = TaskManager()

var task1 = Task(title: "Hashan", descrption: "make Apple IOS", priority: .high)
var task2 = Task(title: "Hashan", descrption: "make Apple IOS", priority: .high)

NewTask.addtask(inputTask: task1)
NewTask.addtask(inputTask: task2)
NewTask.removeTask(index: -9)
NewTask.displayTasks()
