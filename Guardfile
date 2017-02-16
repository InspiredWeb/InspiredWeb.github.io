# A sample Guardfile
# More info at https://github.com/guard/guard#readme

require 'rb-notifu'

Notifu::show :message => "test", :type => :warn, :time => 1 do |status|
  p Notifu::ERRORS.include? status
end

sleep 1.5

notification :notifu, :nosound => true