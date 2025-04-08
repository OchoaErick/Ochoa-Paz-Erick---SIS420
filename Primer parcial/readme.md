







# Normalización
scaler = StandardScaler()
X_train_scaled = scaler.fit_transform(X_train)
X_test_scaled = scaler.transform(X_test)

# Mostrar resultados
X_train_scaled.shape, X_test_scaled.shape, y_train.shape, y_test.shape
