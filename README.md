<div align="left">

  <h2>Hi there 👋</h2>
  
  <p>
    Welcome to my GitHub page! I just finished a Web Development bootcamp at Le Wagon, and I'm looking for my first job as a web developer. 😄
  </p>

  <hr>



  <p><a href="https://miguel-ines.com/" target="_blank">🌐 Portfolio</a></p>
  <p><a href="https://www.linkedin.com/in/miguelines/" target="_blank">💼 LinkedIn</a></p>
  <p><a href="https://www.compawtible.me" target="_blank">🐾 Compawtible</a></p>

</div>

<hr>


```ruby
class Developer
  def initialize()
    @name = "Miguel Inês"
    @stack = ["React", "JavaScript", "NodeJS", "Ruby on Rails", "Ruby", "SQL", "NoSQL", "HTML", "CSS", "Bootstrap", "Tailwind"]
    @age = 32
    @work = "Teaching Assistant at Le Wagon"
    @education = ["Le Wagon", "University of Lisbon"]
    @hobbies = ["Making music", "Sound design", "Working out", "Robotics", "TTRPGs", "Reading", "Gaming"]
    @future_stack = ["React Native"]
  end

  def hello
    puts "Hi, I'm #{@name}, a developer with experience in
    @stack.each do |technology|
      puts "#{technology}, "
    end
    puts "and a lover of #{@hobbies.sample.downcase}!"
  end  

  def looking_for_job?
    true
  end

  def available_for_hire?
    puts looking_for_job? ? "Yep, let's talk! :)" : "Not right now"
  end

  def learn
    puts "I'm currently learning #{@future_stack.first}"
  end
end

