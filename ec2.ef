provider "aws" {
  region     = "us-west-2"
  access_key = "AKIAUJKSA52N3W4ZUOXF"
  secret_key = "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"
}
resource "aws_instance" "myec2" {
  ami           = "ami-082b5a644766e0e6f"
  instance_type = "t2.micro"

  tags = {
    Name = "HelloWorld"
  }
}
