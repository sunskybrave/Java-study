《java核心技术卷1》  
p183——p187  
如果子类能够拥有自己的相等概念，则对称性需求将强制要求使用getClass进行检测  
如果超类定义相等的概念，则可以使用instanceof进行检测  

超类的检测方法 getClass为例   
、、、
    public boolean equals(Object other)
    {
        if(this == other)
            return true;
        if(other == null)
            return false;
        if(getClass() != other.getClass())
            return false;
        Employee temp = (Employee)other;

        return Objects.equals(name,temp.name)
                && age==temp.age
                && salary==temp.salary;
    }
    、、、
