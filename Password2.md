require 'securerandom'

def generate_password(length = 12)
  SecureRandom.alphanumeric(length)
end

puts "Generated Password: #{generate_password}"
