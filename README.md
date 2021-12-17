# UE.Buffer
Unreal Engine Buffer Plugin Documentation

Universal variable type,support c++ and blueprint, void pointer for blueprint.  

For example (C++):  
  
FString String = TEXT("Hello");  
FBuffer Buffer = String;  
FString Result = Buffer.GetRef<FString>();  
  
TCHAR *String = TEXT("Hello");
FBuffer Buffer = String;  
TCHAR *Result = Buffer.Get<FString>();  
